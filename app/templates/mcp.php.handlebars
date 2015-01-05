<?php  if ( ! defined( 'BASEPATH' ) ) exit( 'No direct script access allowed' );

// include base class
if ( ! class_exists( '{{fileName}}_base' ) ) {
	require_once PATH_THIRD.'{{addonSlug}}/base.{{addonSlug}}.php';
}

/**
 * -
 *
 * @package  {{addonName}}
 * @subpackage ThirdParty
 * @category Modules
 * @author     {{authorName}}
 * @copyright  Copyright (c) {{currentYear}} {{authorName}} ({{authorUrl}})
 * @link  {{authorUrl}}
 */

class {{fileName}}_mcp extends {{fileName}}_base {

	/**
	 * Holder for error messages
	 *
	 * @var        string
	 * @access     private
	 */
	private $error_msg = '';


	/**
	 * Constructor
	 *
	 * @access public
	 * @return void
	 */
	public function __construct() {

		parent::__construct();

		// -------------------------------------
		//  Define base url for module
		// -------------------------------------

		$this->set_base_url();

		// --------------------------------------
		// Add themes url for images
		// --------------------------------------

		$this->data['themes_url'] = ee()->config->slash_item( 'theme_folder_url' );

		// --------------------------------------
		// Load JS lib
		// --------------------------------------

		ee()->load->library( 'javascript' );
	}

	/**
	 * Save Data
	 *
	 * @return [type] [description]
	 */
	public function save_data() {
		if ( ! empty( $_POST ) ) {
			var_dump( $_POST );
			die();
		}

		$return_url = $this->base_url ;
		ee()->functions->redirect( $return_url );
	}

	/**
	 * Index Page
	 *
	 * @return [type] [description]
	 */
	public function index() {

		$this->_set_cp_var( 'cp_page_title', lang( 'index' ) );

		// -------------------------------------
		//  Display error message if any
		// -------------------------------------

		if ( $this->error_msg != '' ) {
			return $this->error_msg;
		}

		return $this->view( 'mcp_index' );

	}

	/**
	 * Save Settings
	 *
	 * @return [type] [description]
	 */
	public function save_settings() {

		if ( $new_settings = ee()->input->post( {{addonSlugUp}}_PACKAGE ) ) {

			if ( isset( $new_settings['new_name'] ) ) {
				$this->settings = array_merge( $this->settings, $data );
			}

			$this->saveSettingsToDB( $this->settings );

			$this->_ee_notice( ee()->lang->line( 'extension_settings_saved_success' ) );
		}

		$return_url = $this->base_url ;

		ee()->functions->redirect( $return_url );

	}

	/**
	 * Set cp var
	 *
	 * @access     private
	 * @param string
	 * @param string
	 * @return     void
	 */
	private function _set_cp_var( $key, $val ) {
		if ( version_compare( APP_VER, '2.6.0', '<' ) ) {
			ee()->cp->set_variable( $key, $val );
		}
		else {
			ee()->view->$key = $val;
		}
	}

}

/* End of file mcp.{{addonSlug}}.php */
/* Location: ./system/expressionengine/third_party/{{addonSlug}}/mcp.{{addonSlug}}.php */
