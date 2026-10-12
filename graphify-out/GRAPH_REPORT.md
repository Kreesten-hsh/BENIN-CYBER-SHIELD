# Graph Report - BENIN-CYBER-SHIELD  (2026-10-12)

## Corpus Check
- 320 files · ~253,608 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 32 file(s) not represented in the graph (top: (none) 10, .xml 8, .example 2)

## Summary
- 2110 nodes · 5271 edges · 105 communities (72 shown, 33 thin omitted)
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 145 edges (avg confidence: 0.94)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Evidentiary Dossier & Snapshots
- Database Migrations & Schema
- Admin Businesses Web Management
- SME Administration & Approval Backend
- Threat Intelligence & Geo Heatmap
- Case Bundles & Artifact Storage
- SME Brand Defense UI Layout
- Web UI Design System Components
- Backend API Entrypoints & Analysis
- Admin Web Dashboard Routing
- Admin Alerts UI Management
- Flutter Native Telemetry Bridge
- Mobile App Theme & Styling
- Frontend API Client & Transport
- Backend Alert Lifecycle & Triage
- Citizen Verification & Incident Signals
- Mobile Flutter Presentation Pages
- Threat Ingestion Sources API
- Mobile UI Reusable Widgets
- Incident Exports & STIX Serialization
- Authentication & JWT Security
- Mobile Riverpod State Stores
- FastAPI Lifespan & Bootstrap
- Dashboard Operational Metrics
- Frontend Tooling & Bundling
- History Entry Subsystem
- Mainactivity Subsystem
- Install Store Subsystem
- Main Subsystem
- Report Page Subsystem
- Shield Subsystem
- App Icons Subsystem
- Verify Result Subsystem
- Shieldnotificationorchestrator Subsystem
- History Page Subsystem
- Verifysignalpanel Subsystem
- Tsconfig.App Subsystem
- Mobile Subsystem
- Root Shell Subsystem
- Package Subsystem
- Tsconfig.Node Subsystem
- Settings Page Subsystem
- App Panel Subsystem
- Shieldnotificationlistenerservice Subsystem
- Shieldconfigstore Subsystem
- Native Shield Bridge Subsystem
- Toast Subsystem
- Processor Subsystem
- Seed Demo Data Subsystem
- Package Subsystem
- Engine Subsystem
- Shieldanalysisclient Subsystem
- Router Subsystem
- Monitoringservice Subsystem
- Shieldlocalnotifier Subsystem
- Mobile Api Client Subsystem
- Shieldhistorystore Subsystem
- Button Subsystem
- Use Toast Subsystem
- Shieldpendinganalysisstore Subsystem
- Result Page Subsystem
- External Receivers Subsystem
- Mobile Shield Settings Subsystem
- Report Result Subsystem
- Main Subsystem
- Providers Subsystem
- B7D4C9A12Ef0 Add Owner User Id On Alerts And Sources Subsystem
- Evidence Subsystem
- Bootstrap Data Subsystem
- Native Shield Status Subsystem
- Threatmappage Subsystem
- Vercel Subsystem
- Env Subsystem
- Analysis Subsystem
- Shield Subsystem
- 21349Ec1Bb04 Add Last Status To Monitoring Sources Subsystem
- E1F2A3B4C5D6 Align Legacy Evidences Columns Subsystem
- E8F9A1B2C3D4 Simplify Alert Workflow Subsystem
- Package Subsystem
- Config Subsystem
- Generate Icons Subsystem
- Installpwa Subsystem
- Providers Subsystem
- Operators Subsystem
- Verify Cold Start Subsystem
- Comingsoonpage Subsystem
- Tailwind.Config Subsystem
- Tsconfig Subsystem
- Serve Fake Site Subsystem

## God Nodes (most connected - your core abstractions)
1. `APIResponse` - 66 edges
2. `lucide-react` - 42 edges
3. `react` - 42 edges
4. `Badge()` - 42 edges
5. `App()` - 36 edges
6. `PageHero()` - 34 edges
7. `cn()` - 33 edges
8. `FormalReport` - 32 edges
9. `create_citizen_report()` - 32 edges
10. `apiClient` - 31 edges

## Surprising Connections (you probably didn't know these)
- `Public Citizen Portal` --authenticates_against--> `login()`  [INFERRED]
  README.md → backend/app/api/v1/endpoints/auth.py
- `National Admin Console` --queries--> `get_critical_threats()`  [INFERRED]
  README.md → backend/app/api/v1/endpoints/dashboard.py
- `National Admin Console` --displays--> `get_threat_intel_dashboard()`  [INFERRED]
  README.md → backend/app/api/v1/endpoints/threat_intel.py
- `read_admin_dashboard()` --uses--> `APIResponse`  [INFERRED]
  backend/app/api/v1/endpoints/admin_console.py → backend/app/schemas/response.py
- `read_admin_transmissions()` --uses--> `APIResponse`  [INFERRED]
  backend/app/api/v1/endpoints/admin_console.py → backend/app/schemas/response.py

## Import Cycles
- None detected.

## Communities (105 total, 33 thin omitted)

### Community 0 - "Evidentiary Dossier & Snapshots"
Cohesion: 0.05
Nodes (72): _build_formal_report_snapshot(), _create_bundle_for_formal_report(), _serialize_legacy_evidence(), _serialize_memory_evidence(), CitizenMessage, EvidenceItem, ExternalTransmission, ForensicBundle (+64 more)

### Community 1 - "Database Migrations & Schema"
Cohesion: 0.05
Nodes (20): upgrade(), upgrade(), upgrade(), _default_business_name(), upgrade(), upgrade(), upgrade(), upgrade() (+12 more)

### Community 2 - "Admin Businesses Web Management"
Cohesion: 0.04
Nodes (63): AdminBusinessesPage(), parseCommaSeparated(), STATUS_OPTIONS, statusVariant(), AdminDashboardPage(), CATEGORY_COLORS, categoryFallback(), ChartSkeleton() (+55 more)

### Community 3 - "SME Administration & Approval Backend"
Cohesion: 0.11
Nodes (45): approve_business(), create_admin_business(), disable_business(), read_admin_business_detail(), read_admin_businesses(), reject_business(), patch_pme_profile(), read_pme_dashboard() (+37 more)

### Community 4 - "Threat Intelligence & Geo Heatmap"
Cohesion: 0.07
Nodes (41): read_map_overview(), ThreatIndicator, DepartmentMapPoint, MapOverviewData, MapOverviewTransmissionItem, derive_department_from_phone(), normalize_department_name(), resolve_department() (+33 more)

### Community 5 - "Case Bundles & Artifact Storage"
Cohesion: 0.06
Nodes (36): _artifact_write_root(), _bundle_alert_uuid(), _candidate_artifact_paths(), _delete_relative_artifact(), delete_report(), download_case_bundle(), download_json(), download_pdf() (+28 more)

### Community 6 - "SME Brand Defense UI Layout"
Cohesion: 0.08
Nodes (44): BrandLockup(), BrandLockupProps, businessNavItems, BusinessSidebar(), BusinessSidebarProps, BusinessTopbar(), BusinessTopbarProps, navItems (+36 more)

### Community 7 - "Web UI Design System Components"
Cohesion: 0.11
Nodes (40): PageHero(), PageHeroProps, Badge(), BadgeProps, variants, AdminBusinessDetailPage(), statusVariant(), AnalysisPage() (+32 more)

### Community 8 - "Backend API Entrypoints & Analysis"
Cohesion: 0.12
Nodes (16): run_migrations_offline(), _serialize_legacy_report(), _utc_now(), authenticate_user(), AuthenticatedPrincipal, _decode_token_or_raise(), get_current_active_principal(), get_current_subject() (+8 more)

### Community 9 - "Admin Web Dashboard Routing"
Cohesion: 0.07
Nodes (42): AdminBusinessDetailPage, AdminBusinessesPage, AdminDashboardPage, AdminExportsPage, AdminSettingsPage, AdminTransmissionsPage, AlertsPage, AnalysisPage (+34 more)

### Community 10 - "Admin Alerts UI Management"
Cohesion: 0.08
Nodes (42): ConfirmDialog(), ConfirmDialogProps, AlertsPage(), AlertsPageProps, isCitizenSource(), STATUS_OPTIONS, ApiErrorPayload, AttachmentPreview() (+34 more)

### Community 11 - "Flutter Native Telemetry Bridge"
Cohesion: 0.04
Nodes (39): apiClientProvider, _applySettings, attachments, bootstrapProvider, clear, client, copyWith, created (+31 more)

### Community 12 - "Mobile App Theme & Styling"
Cohesion: 0.04
Nodes (32): background, backgroundSoft, base, baseTextTheme, BeninShieldColors, BeninShieldThemeX, brand, brandSoft (+24 more)

### Community 13 - "Frontend API Client & Transport"
Cohesion: 0.12
Nodes (29): apiClient, APIResponse, CampaignAlert, CampaignBanner(), CampaignSummaryResponse, formatDate(), useToast(), AdminExportsPage() (+21 more)

### Community 14 - "Backend Alert Lifecycle & Triage"
Cohesion: 0.10
Nodes (22): delete_alert(), _normalize_alert_status(), read_alert(), read_alerts(), _serialize_alert(), update_alert(), AlertBase, AlertResponse (+14 more)

### Community 15 - "Citizen Verification & Incident Signals"
Cohesion: 0.10
Nodes (18): public_verify_signal(), decide_incident(), delete_citizen_incident(), read_citizen_incident(), read_citizen_incidents(), read_citizen_top_numbers(), report_incident(), report_incident_with_media() (+10 more)

### Community 16 - "Mobile Flutter Presentation Pages"
Cohesion: 0.08
Nodes (14): AboutPage, build, build, _controller, createState, _currentIndex, BrandBar, build (+6 more)

### Community 17 - "Threat Ingestion Sources API"
Cohesion: 0.12
Nodes (18): create_source(), delete_source(), read_runs(), read_source(), read_source_runs(), read_sources(), toggle_source(), update_source() (+10 more)

### Community 18 - "Mobile UI Reusable Widgets"
Cohesion: 0.07
Nodes (33): _DetailPill, _GlassNavItem, _AppToggleTile, _SectionHeader, _SettingSwitchRow, _StatusInlineRow, _SvgAssetIcon, accent (+25 more)

### Community 19 - "Incident Exports & STIX Serialization"
Cohesion: 0.17
Nodes (23): export_admin_csv(), export_admin_stix_lite(), read_admin_dashboard(), read_admin_transmissions(), AdminCategoryCount, AdminDailyCount, AdminDashboardBusinessTargetItem, AdminDashboardData (+15 more)

### Community 20 - "Authentication & JWT Security"
Cohesion: 0.12
Nodes (19): _authenticate_or_raise(), change_password(), ChangePasswordRequest, login(), login_access_token(), LoginRequest, create_access_token(), get_password_hash() (+11 more)

### Community 21 - "Mobile Riverpod State Stores"
Cohesion: 0.11
Nodes (29): build, historyProvider, installStoreProvider, mobileShieldSettingsProvider, nativeShieldBridgeProvider, nativeShieldStatusProvider, themeModeProvider, build (+21 more)

### Community 22 - "FastAPI Lifespan & Bootstrap"
Cohesion: 0.11
Nodes (12): setup_logging(), Alert, AnalysisResult, Evidence, _append_analysis_note(), _build_failure_message(), _clamp_risk_score(), process_result() (+4 more)

### Community 23 - "Dashboard Operational Metrics"
Cohesion: 0.09
Nodes (17): get_active_sources(), get_critical_threats(), get_dashboard_stats(), get_reports_count(), get_weekly_stats(), export_threat_intel(), get_campaign_summary(), get_map_heatmap() (+9 more)

### Community 24 - "Frontend Tooling & Bundling"
Cohesion: 0.09
Nodes (25): name, private, type, version, autoprefixer, eslint, @eslint/js, eslint-plugin-react-hooks (+17 more)

### Community 25 - "History Entry Subsystem"
Cohesion: 0.07
Nodes (28): categoriesDetected, color, createdAt, end, explanation, fonAlert, fonAlertSpeech, fromJson (+20 more)

### Community 27 - "Install Store Subsystem"
Cohesion: 0.07
Nodes (23): _, apiBaseUrl, AppConfig, minSupportedVersion, cacheHistoryJson, clearLocalData, _deviceInstallIdKey, _historyCacheKey (+15 more)

### Community 28 - "Main Subsystem"
Cohesion: 0.13
Nodes (12): IngestionRequest, manual_ingestion(), health_check(), lifespan(), _enqueue_forensic_capture(), _requeue_after_delay(), start_external_transmission_consumer(), consume_results() (+4 more)

### Community 29 - "Report Page Subsystem"
Cohesion: 0.09
Nodes (18): BeninCyberShieldApp, reportControllerProvider, verifyControllerProvider, build, ReportConfirmationPage, build, createState, _files (+10 more)

### Community 30 - "Shield Subsystem"
Cohesion: 0.26
Nodes (19): IncidentDecisionData, IncidentDecisionRequest, OperatorActionStatusData, OperatorActionStatusRequest, ShieldActionTimelineItem, ShieldDispatchData, ShieldDispatchRequest, ShieldIncidentTimelineData (+11 more)

### Community 31 - "App Icons Subsystem"
Cohesion: 0.08
Nodes (25): _, analytics_rounded, apps_rounded, battery_saver_rounded, bolt_rounded, check_circle_rounded, circle, contrast_rounded (+17 more)

### Community 32 - "Verify Result Subsystem"
Cohesion: 0.08
Nodes (25): categoriesDetected, citizenAdvice, color, departmentSource, end, explanation, fonAlert, fonAlertSpeech (+17 more)

### Community 33 - "Shieldnotificationorchestrator Subsystem"
Cohesion: 0.14
Nodes (6): OfficialOperatorMessageGuard, AnalysisPersistenceOutcome, DROPPED, PROCESSED, RETRYABLE_FAILURE, ShieldNotificationOrchestrator

### Community 34 - "History Page Subsystem"
Cohesion: 0.09
Nodes (19): _buildHighlightedMessage, createState, didChangeAppLifecycleState, _displayFilterLabel, dispose, _filter, _highlightColor, _HistoryFilter (+11 more)

### Community 35 - "Verifysignalpanel Subsystem"
Cohesion: 0.13
Nodes (20): COLOR_CLASSES, HighlightedMessage(), Props, RULE_TOOLTIPS, Span, detectCitizenChannel(), getPreferredFonVoice(), getVerifyErrorMessage() (+12 more)

### Community 36 - "Tsconfig.App Subsystem"
Cohesion: 0.09
Nodes (21): compilerOptions, allowImportingTsExtensions, baseUrl, isolatedModules, jsx, lib, module, moduleDetection (+13 more)

### Community 37 - "Mobile Subsystem"
Cohesion: 0.20
Nodes (8): mobile_bootstrap(), mobile_history(), normalize_risk_level(), MobileBootstrapData, MobileHistoryData, MobileHistoryItem, fetch_mobile_history(), get_mobile_bootstrap_payload()

### Community 38 - "Root Shell Subsystem"
Cohesion: 0.10
Nodes (14): build, createState, didChangeAppLifecycleState, dispose, _foregroundSyncTimer, icon, initState, label (+6 more)

### Community 39 - "Package Subsystem"
Cohesion: 0.10
Nodes (20): dependencies, axios, class-variance-authority, clsx, date-fns, lucide-react, @radix-ui/react-label, @radix-ui/react-radio-group (+12 more)

### Community 40 - "Tsconfig.Node Subsystem"
Cohesion: 0.10
Nodes (19): compilerOptions, allowImportingTsExtensions, erasableSyntaxOnly, lib, module, moduleDetection, moduleResolution, noEmit (+11 more)

### Community 41 - "Settings Page Subsystem"
Cohesion: 0.10
Nodes (17): active, assetName, color, createState, didChangeAppLifecycleState, dispose, fallbackIcon, icon (+9 more)

### Community 42 - "App Panel Subsystem"
Cohesion: 0.11
Nodes (14): AppPanel, backgroundOpacity, build, child, glowColor, padding, radius, showInnerBorder (+6 more)

### Community 44 - "Shieldconfigstore Subsystem"
Cohesion: 0.16
Nodes (3): ShieldConfig, ShieldConfigStore, ShieldRuntimeStatus

### Community 45 - "Native Shield Bridge Subsystem"
Cohesion: 0.11
Nodes (13): _channel, consumePendingOpenSurface, fetchLocalHistory, flushPendingQueue, getShieldSettings, getShieldStatus, NativeShieldBridge, openNotificationAccessSettings (+5 more)

### Community 46 - "Toast Subsystem"
Cohesion: 0.22
Nodes (15): RadioGroup, RadioGroupItem, Toast, ToastAction, ToastActionElement, ToastClose, ToastDescription, ToastProps (+7 more)

### Community 47 - "Processor Subsystem"
Cohesion: 0.17
Nodes (7): FraudAnalyzer, build_failed_report(), is_valid_http_url(), process_task(), run_worker(), utc_now_iso(), validate_task_payload()

### Community 48 - "Seed Demo Data Subsystem"
Cohesion: 0.26
Nodes (10): _build_pme_messages(), _confirm_incident(), _dispatch_shield(), _extract_url(), _login(), _login_with_credentials(), main(), _require_admin_credentials() (+2 more)

### Community 49 - "Package Subsystem"
Cohesion: 0.12
Nodes (17): devDependencies, autoprefixer, eslint, @eslint/js, eslint-plugin-react-hooks, eslint-plugin-react-refresh, globals, postcss (+9 more)

### Community 51 - "Shieldanalysisclient Subsystem"
Cohesion: 0.21
Nodes (4): ShieldAnalysisAttempt, ShieldAnalysisClient, ShieldAnalysisResult, ShieldHighlightedSpan

### Community 52 - "Router Subsystem"
Cohesion: 0.12
Nodes (3): appRouter, _rootNavigatorKey, main

### Community 53 - "Monitoringservice Subsystem"
Cohesion: 0.24
Nodes (11): BusinessMonitoringPage(), AddSourceDialog(), AddSourceDialogProps, MonitoringPage(), MonitoringPageProps, SourceDetailPage(), monitoringService, MonitoringSource (+3 more)

### Community 55 - "Mobile Api Client Subsystem"
Cohesion: 0.13
Nodes (7): _dio, _extractData, fetchBootstrap, fetchHistory, MobileApiClient, submitReport, verify

### Community 56 - "Shieldhistorystore Subsystem"
Cohesion: 0.24
Nodes (3): ShieldHistoryHighlightedSpan, ShieldHistoryRecord, ShieldHistoryStore

### Community 57 - "Button Subsystem"
Cohesion: 0.21
Nodes (9): Button, ButtonProps, buttonVariants, Label, labelVariants, class-variance-authority, clsx, @radix-ui/react-slot (+1 more)

### Community 58 - "Use Toast Subsystem"
Cohesion: 0.22
Nodes (12): Action, ActionType, addToRemoveQueue(), dispatch(), genId(), listeners, memoryState, reducer() (+4 more)

### Community 60 - "Result Page Subsystem"
Cohesion: 0.18
Nodes (8): createState, _estimateFonSpeechDuration, _highlightColor, _isSpeakingFon, ResultPage, _ResultPageState, _riskColor, _share

### Community 61 - "External Receivers Subsystem"
Cohesion: 0.36
Nodes (5): receive_anssi_ocrc_payload(), receive_operator_payload(), _validate_secret(), ExternalDeliveryAckData, build_external_delivery_ack()

### Community 62 - "Mobile Shield Settings Subsystem"
Cohesion: 0.18
Nodes (8): activeChannelCount, alertMedium, alertThreshold, copyWith, hasActiveMonitoring, monitorMessenger, monitorSms, monitorWhatsapp

### Community 63 - "Report Result Subsystem"
Cohesion: 0.20
Nodes (8): alertUuid, fromJson, publicReference, queuedForOsint, ReportResult, reportUuid, riskScoreInitial, status

### Community 64 - "Main Subsystem"
Cohesion: 0.33
Nodes (3): global_exception_handler(), http_exception_handler(), validation_exception_handler()

### Community 65 - "Providers Subsystem"
Cohesion: 0.22
Nodes (7): MobileShieldSettingsController, ReportController, ReportState, ThemeModeController, VerifyController, VerifyState, MobileShieldSettings

### Community 66 - "B7D4C9A12Ef0 Add Owner User Id On Alerts And Sources Subsystem"
Cohesion: 0.68
Nodes (7): downgrade(), _get_inspector(), _has_column(), _has_foreign_key(), _has_index(), _has_table(), upgrade()

### Community 67 - "Evidence Subsystem"
Cohesion: 0.32
Nodes (4): get_evidence_file(), read_evidences(), view_evidence_by_id(), view_evidence_item_by_id()

### Community 68 - "Bootstrap Data Subsystem"
Cohesion: 0.25
Nodes (5): beninDepartments, BootstrapData, departments, fromJson, minimumSupportedVersion

### Community 69 - "Native Shield Status Subsystem"
Cohesion: 0.25
Nodes (7): batteryOptimizationIgnored, fromJson, NativeShieldStatus, notificationAccessGranted, pendingQueueCount, postNotificationsGranted, serviceReady

### Community 70 - "Threatmappage Subsystem"
Cohesion: 0.33
Nodes (6): CategoryItem, ChartSkeleton(), ThreatIntelDashboard, ThreatMapPage(), TopNumber, recharts

### Community 71 - "Vercel Subsystem"
Cohesion: 0.29
Nodes (6): buildCommand, framework, installCommand, outputDirectory, rewrites, $schema

### Community 72 - "Env Subsystem"
Cohesion: 0.33
Nodes (3): do_run_migrations(), run_async_migrations(), run_migrations_online()

### Community 75 - "21349Ec1Bb04 Add Last Status To Monitoring Sources Subsystem"
Cohesion: 0.80
Nodes (4): downgrade(), _has_column(), _has_table(), upgrade()

### Community 76 - "E1F2A3B4C5D6 Align Legacy Evidences Columns Subsystem"
Cohesion: 0.80
Nodes (4): _column_names(), downgrade(), _index_names(), upgrade()

### Community 78 - "Package Subsystem"
Cohesion: 0.40
Nodes (5): scripts, build, dev, lint, preview

### Community 82 - "Providers Subsystem"
Cohesion: 0.67
Nodes (4): deviceInstallIdProvider, onboardingCompletedProvider, _bootstrap, _SplashPageState

## Knowledge Gaps
- **335 isolated node(s):** `@radix-ui/react-label`, `@tanstack/react-table`, `react-is`, `@types/node`, `@types/react` (+330 more)
  These have ≤1 connection - possible missing edges. (Counts symbols only; 824 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **33 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `ShieldPendingAnalysisStore` connect `Shieldpendinganalysisstore Subsystem` to `Shieldnotificationorchestrator Subsystem`?**
  _High betweenness centrality (0.054) - this node is a cross-community bridge._
- **Are the 47 inferred relationships involving `APIResponse` (e.g. with `read_admin_dashboard()` and `read_admin_transmissions()`) actually correct?**
  _`APIResponse` has 47 INFERRED edges - model-reasoned connections that need verification._
- **What connects `@radix-ui/react-label`, `@tanstack/react-table`, `react-is` to the rest of the system?**
  _335 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Evidentiary Dossier & Snapshots` be split into smaller, more focused modules?**
  _Cohesion score 0.0545361875637105 - nodes in this community are weakly interconnected._
- **Why does `ShieldNotificationOrchestrator` connect `Shieldnotificationorchestrator Subsystem` to `Shieldnotificationlistenerservice Subsystem`, `Shieldconfigstore Subsystem`, `Shieldanalysisclient Subsystem`, `Shieldlocalnotifier Subsystem`, `Shieldhistorystore Subsystem`, `Mainactivity Subsystem`, `Shieldpendinganalysisstore Subsystem`?**
  _High betweenness centrality (0.054) - this node is a cross-community bridge._
- **Should `Database Migrations & Schema` be split into smaller, more focused modules?**
  _Cohesion score 0.053923541247484906 - nodes in this community are weakly interconnected._
- **Why does `HistoryEntry` connect `History Entry Subsystem` to `Mobile UI Reusable Widgets`?**
  _High betweenness centrality (0.033) - this node is a cross-community bridge._