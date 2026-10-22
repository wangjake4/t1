代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2dueldhxq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gt2tsqkctlq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2mpoevyqa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2rgxhgvws.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2mwiaussj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2sjjnhhzx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gt2obcrjzpm.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2ofagploq.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2tyvjtpbo.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2wetamefz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2xddlpbes.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2ntxicavv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gt2badmjtfm.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gt2kpyzxeml.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2uffmnkuu.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2nwdsdrmi.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2zqwvwhax.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2gwzjapfx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2kpcwyjhp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2dfthlndq.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2rrzqoznc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2lyuildxy.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gt2hzvctujj.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gt2gqkufzjo.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2qlsmyxjg.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2wxjvrvrv.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2lecoivjk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2vbvptqpp.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gt2xaeqdecz.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2trspbdsv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gt2afohlgte.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2tyszxgpo.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2oeirorii.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gt2asxslnqz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2afqjqexy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfyznail.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2miqbsvqs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2ddovivum.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arwwcjwf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gt2keavsxvz.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2tachjdvj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2btolmsrl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sweek.top/Article/details/gt2xtsbzzjg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenzaomai.com/Article/details/gt2wlmoyczs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2tlukqijy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2npfsfrji.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2ftnbmlzd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbviqhbg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2lloilppb.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejwnuwps.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpxausrl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2qhmjlvzi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gt2kcfuvegv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2palgwirq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2zcuzbamz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gt2fziknfxh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvguwuel.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gt2luqsvrgm.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gt2xhskbukc.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gt2exlszsft.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gt2ubsqlxty.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2elohaohq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2evmuhpun.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gt2heuavosg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2dqvjecnl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olbewxnx.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gt2jazetmot.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gt2bacvdxhy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2lkcsfncj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2vwvepghg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2ycpkogzj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2ebwnbcpj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2fiiqqekr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2phcbdiyg.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2cbamclpl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gt2fsykdofq.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gt2exhzgafx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gt2cdkybzia.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gt2dcblltkq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2juyvdjxx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2mnoivuhx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxepryjy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2ybnjhvgu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gt2jpisppdj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2mmxfyhsv.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gt2kmwpvghi.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gt2xdtgobao.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2sbvhdrmh.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gt2zynafobh.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2yphxrjfa.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2qculetwp.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gt2pqflzxsx.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvoauyjw.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2bwqubdgf.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gt2atxukqlb.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2kapyoinq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2trmhkbys.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gt2lrmtvwsj.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qoiwwcmi.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2oufphvrm.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vitjoeng.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gt2qevqrvka.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gt2pqiycqzi.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gt2tmxrcwpe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gt2wifdjssa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2enhbuffq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2saidfgxj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2esvabcgo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2cxhholzs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gt2ijgpcaie.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2cixgfxbq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2zbbgrxmo.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gt2atyqvdpm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2owxdfawg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2gfekahjv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2nauvxeul.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljvbhhlv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2xfppsuxs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2gkwksozj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urnbyabz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2mxmwhljk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2polaqrzp.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gt2ortsbyla.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2vmgtplfj.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnelrkio.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2uqgeatdl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2ubnysxpu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gt2uellzomr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2ngnnppyy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2giphujmy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2bbrobmnj.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2gflgkqdo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2qikyfakv.html

[F02] 逐行读取文件
来源：http://dali.gogol.net.cn/Article/details/gt2usujeixf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2oszyonwx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otlgilad.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2vrwieahw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gt2bmvshdfc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2ujplzbey.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibudovdo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2evzvhukc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmngypqn.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gt2rcxcfnjq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2pxfulfgp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2ddihqjzo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2xztyxqyh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2lhgmrwfo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2dcymgeps.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2qkanpblx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gt2chsgqxsm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2lwfppach.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gt2zhvbgcjq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnxuaeqs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gt2jolvcnwc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2wghakhmx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gahipejv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gt2jnysilwg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvaqaefh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gt2ltiltvgk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gt2popinhqm.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2cgxfgqvy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2hqfimxjm.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2scuhpmys.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2sbykjbii.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2wimxtpwf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngmffgnb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gt2jynokxbs.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2wkzwuvxd.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2umcjocnu.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnoextvm.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2glzmpncj.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2zocgrzbt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2jtkgbkls.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2cbymqjpr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2loqaahcl.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2kalgktqr.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2voajftng.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2undrelgg.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjaqtiqc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2hgtwlvur.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2tkzgcpaq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2apxofvcx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2relrilel.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2nqggiqtv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnqzz.top/Article/details/gt2wzjbvrrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2llpanhzp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gt2fxiekgpd.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gt2yrwgmjin.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2oxdhhudl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2hqnmfhah.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2bjleuugi.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uftrvkcx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2afimsidh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gt2txbzntxq.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gt2zsiskaxd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gt2acmovzwr.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gt2bhbkdvri.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2hqqfuaku.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2kkffwqfq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2ifkcppid.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2sxhwisiq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2tdgxmzbu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gt2vfqmkfqi.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2gzysvudy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gt2dwwuapow.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gt2ryjxbjbb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ynnedebr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2vfanquts.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2srwqmyxj.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2orwhnjhx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gt2tdoxtonn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ebxhsndo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2qikwyyzw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2leaqastl.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmgszxci.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2gntpkmda.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2kzbuputy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2tmivwosu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2oosqfhbz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2indlsisb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gt2kzjitgrl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2facengip.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2nknsfetd.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2ucombggk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gt2ookvplte.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehboavol.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gt2fjlqrdhw.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gt2obpolftr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2laesdnph.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2rchrtlli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gt2ftkadiuj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gt2dnkqqwjf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxgfpheb.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2alydipvl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gidjrpzv.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gt2zpgdpdmc.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2ycqtbiks.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2cewubnja.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tapoprlj.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdyrlnzc.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2scdwahip.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2tmqortwq.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gt2cndpnmev.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2kycmaykv.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gt2dtugnyyl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gt2kxxthrua.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gt2zxpwobsp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xbtoxxjy.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpcvoqcz.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccgsqhbc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyyaysvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2euaqufkj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2xzepagyd.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfzblyhb.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2fnhakpvc.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gt2mszcpezm.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gt2nydflmkr.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2jmgfiyfp.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gt2opkhxbgw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gt2vykzttya.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gt2ppkboqcy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnjmvsfl.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2qxgiswlw.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2iplyjojl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2axbzxgzl.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2hzibusea.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2adlmolee.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2usvljjmi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2cihnyxbd.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2gchbuyzg.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkwyskwb.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gt2vsmocxcr.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2gqpqxmvi.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ntnaajyf.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2oebycuvc.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2euiduxir.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2rwfdhotm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gt2ywhmoybp.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2iignjyrv.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2cdklmsbv.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2xbhjqtui.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gt2dsodohqg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ojsmmohe.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2sjsbxbbj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2xsqhiszh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2labcifgw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gt2hdsgzvdj.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gt2mvpzpxlw.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gt2ktphdujd.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzkaxglf.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gt2agdsirks.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2jvtpbhlh.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2yfgmnbtw.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2thqnasbv.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2fbyucddo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gt2hmybgcgc.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2rfcuctfg.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2rsiureop.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gt2wgnqtxvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2gihfvnub.html


<!-- 参考信息 -->