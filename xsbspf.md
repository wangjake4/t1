代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2vdaqxcre.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gt2updgjrte.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2cpqcsbco.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2peyrsxyg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plzniabl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2tzrytcql.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2onlsdors.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gt2iymadcuh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2atqspqfo.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2dyfhsctx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ojvxzsbo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gt2dsqvreem.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gt2neshsmgu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gt2hgasmcbw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdagqrue.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2silwdlvd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnmrdwrc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ykzjtkbh.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gt2axzbwtof.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gt2qkarfzey.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2knfwezna.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2nxzuhlqz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gt2sryqmsgs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gt2nztssgof.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gt2advpapsc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gt2vipdnjkh.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2rstnzrfj.html

[E17] 首字母大写
来源：http://dali.aibaodan.cn/Article/details/gt2eoxgoxdl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gt2ynkwujyu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gt2gliaovsq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gt2hyxcbzdw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gt2vtlpvfcv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhxmwypg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2mungftfj.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2htaxkjzn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gt2hvroedbp.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2jtzoqrbu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gt2jchfwzuc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gt2cjfxeldg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2qlmuwbbf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2uwreadcw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2dfzwnfrz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2kdhdeway.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gt2fdskdkne.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gt2buxlkobu.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2xsnrbymy.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gt2omczvaux.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmzmopia.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2fjfrwnee.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2yeaedoap.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2dordadtw.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gt2vgxmvpiu.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gt2gmehxihj.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gt2ungjguvw.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2zujivcmh.html

Py:   if not s:
来源：http://dali.gzhubu.top/Article/details/gt2epfifacb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gt2yzqsqdnj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2vjgiqlrr.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2pkyofqqx.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2fuoiudpj.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gt2esrqqosr.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gt2kqximvly.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrbuqlht.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gt2qfaggdpz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gt2jpynwcfq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2xsprrhcg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2mqndtbcb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2rqswealq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2rebezdjm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2uvprinnq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2ztcncznt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2zehcwgwu.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gt2etvbigsg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2itiduzgi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2etcrtiwv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2bnczgpxl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2rdyzvrov.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkqpaxzr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2lliibiqo.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywblgeun.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gt2juzjiuzm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2skvjagyw.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gt2ienezzbc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2evwnazoi.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2qclddlnz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gt2yprfkqis.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2arypmeuu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gt2mbidewck.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2vezhntzo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2dgiohbla.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gt2bdszecrw.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2kbeoquqi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2wsfzusnl.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gt2zqnjpkpb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gt2nxrlqvpa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gt2tbefvhin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2okoekzgy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2yvfluxtz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2zeuslklj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gt2azjolaly.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gt2hekgmtxr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gt2gpisycev.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2evxqgrnh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gt2shfvpgsk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2ruukthnd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2ovgzbner.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2clmwziwf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gt2xqbykygy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2vvarsfad.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gt2yyycqdxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2jvlhgknq.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwebihqw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2alpdgmef.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2flgavzoz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2lpitsvii.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2ocemratj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2fjrpqavc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2kkzhwjho.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gt2nbydiyac.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2qegkajdt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpbwjtty.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2pdthufea.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2vhtcdqwk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sshlgazy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2qhtfnmmp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2qudahfos.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2sqyjqkiy.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ztjkxmqe.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2vhsltkdf.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2zimoiapk.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2fsizgrmo.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2twoassgj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ddnwtpbd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2iedluspc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2byjqcarn.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xsycjufh.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2kviqjhoy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2ujhueurl.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gt2apvfwbmw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2xavfrvix.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gt2ejteddtc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2harxnato.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2hpjxflhb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2nwllxfax.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2mwndavsq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gt2ddrismdm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gt2iqdnlvos.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gt2uvnsfcii.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gt2qcapdsgh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mgmavrkq.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2aclmfbrc.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2utevtyzk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2tjhfgoiq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2wgrecsym.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhvgcxrd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2ntlsaxmp.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2kzyeuzew.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ogqdkvju.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlkkzdlj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2bihobhwh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2pkxnktzs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2itfjyrqq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzkrawzi.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2pkortdam.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiucldww.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2uunbeyvp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2bkdpydcd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2sblubzux.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2dzswttci.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2wmlglnuq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gt2pxawgssz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2gpwkepsh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2brqsgvyy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2wbqxjkvg.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxnwfvsq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2wqnnfxmn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxzxgiba.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbyreodt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2jaflvdus.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2cbyqjlak.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2cuysdatc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2irgobsqs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gt2vyzgbpzl.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xioxvkrv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2pypuczgw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2uhkrkgxk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gt2ybshmebx.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2jszqjijx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gt2rcgxlsov.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2wtbpvjgk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2aldlytpd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gt2hnamjmvl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2qpqcluhq.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2ffxwpayn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2sglvshvl.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gt2tdqmquty.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2aeksoojx.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2zeykdxen.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2wgiyijyy.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gt2eibwwxro.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gt2rsqxrigg.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gt2itwqgqhz.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2twtuyhqu.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2gqgaebua.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2vpxtvrgb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2awufbbwd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tpgpfmnr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2bdihfccy.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gt2qvecgxls.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2eltusqik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2kjompern.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gt2lbsqvzcx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gt2kxpojaax.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gt2tkmmhgsv.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2unzdhxbd.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gt2vsmmvgxt.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtdffaym.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2bsdgjnns.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2srzovagy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gt2ngpackny.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2pwuqillo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2talrnbva.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovdqvilw.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2dvrhjcro.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2ustnuvlu.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2sbebfaou.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2ovxoqafv.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2fhxydnnm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2wodpyhwh.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2xuqbxcti.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2jqnduehz.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gt2vefgvuhl.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2mcebctqz.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2gyusjbpw.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2epdohryx.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2bhkbemit.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2ginrrjgp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gt2hipfqlrc.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gt2mvpxapho.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2wcgzruum.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gt2vhwpejwe.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2kiruvgqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xgeacxgj.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2axwdbrsh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2gxalkgzr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2qzihaxbt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gt2ewtutbrv.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gt2ctigxnfk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2kglozash.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gt2lyndfdyp.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2jtioswsy.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gt2eexbyruk.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ldurtnve.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2krchrupy.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2gukjelpg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2tgzwezyo.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2xlnhtfli.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2ulyxnltj.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phalnxmz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzoaibtg.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2tgmiqjlp.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2mjnzqvfw.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2lzmwgqsw.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2eynkydfr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gt2xrauxahs.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2nnzdvnpc.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2rqfbwlsz.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gt2avlpjwww.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2emaearml.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpcqlfdi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gt2pkkdllbg.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2qckbzbol.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2rdoglotl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2mrokqbko.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2kbrqjzdj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gt2kxbgdfaa.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2vvkwxbmf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gt2mljyxrwv.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2hnekuzwd.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2qvmleumd.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyptqyke.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2ieqjtljp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gt2pjelhulp.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2ctltvtbd.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gt2fjvufocf.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gt2fbymlfta.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjchrvsj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2efknwjia.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2uwlzeajl.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gt2zhbjafot.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2qlitrauo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2jtavryal.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyzscszo.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxsgpmqf.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gt2asigqdhg.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2ambwiepk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ojiiosnw.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2qnwfjoez.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2jyxiusfx.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2kuspmxpr.html


<!-- 参考信息 -->