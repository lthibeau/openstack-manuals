..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _nova-barbican:

.. list-table:: Description of Barbican configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - **[barbican]**
     -
   * - ``cafile`` = ``None``
     - (String) PEM encoded Certificate Authority to use when verifying HTTPs connections.
   * - ``catalog_info`` = ``key-manager:barbican:public``
     - (String) Info to match when looking for barbican in the service catalog. Format is: separated values of the form: <service_type>:<service_name>:<endpoint_type>
   * - ``certfile`` = ``None``
     - (String) PEM encoded client certificate cert file
   * - ``endpoint_template`` = ``None``
     - (String) Override service catalog lookup with template for barbican endpoint e.g. http://localhost:9311/v1/%(project_id)s
   * - ``insecure`` = ``False``
     - (Boolean) Verify HTTPS connections.
   * - ``keyfile`` = ``None``
     - (String) PEM encoded client certificate key file
   * - ``os_region_name`` = ``None``
     - (String) Region name of this node
   * - ``timeout`` = ``None``
     - (Integer) Timeout value for http requests
   * - **[certificates]**
     -
   * - ``barbican_auth`` = ``barbican_acl_auth``
     - (String) Name of the Barbican authentication method to use
   * - ``cert_manager_type`` = ``barbican``
     - (String) Certificate Manager plugin. Defaults to barbican.
