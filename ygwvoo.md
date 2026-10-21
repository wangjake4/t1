代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtqwpevmxn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtcepszjgq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtjfxkonxy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtbxshohaf.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gtdufwxbtc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtvcvxczpo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtxhrhiipe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavsqhxkn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtmpmmhqam.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtetgzlkfo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaynachmp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gtwuqhqtjc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gtnycynlys.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtarwafgqk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gtzbrjcmld.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtxwbdloic.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gthjpzvvxx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtepaxhojr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gtyddvvbri.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtambpklpw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gtteoqfnvj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppviokcs.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtycmeyamq.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtnpzelfaf.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtnyahlifg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtclbcgihq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtginmuwzt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtymwmnfwy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtlpujckkl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtqdwsaqnx.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtznqgficf.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtldwasuto.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gtjepkhtme.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtpsejbawk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gthrkumqfy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtoqjwnstd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtjzlblluc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gtaotlghza.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtbynuvfeu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gttwybilqq.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gttjonpynt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gtzzmgpxil.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtjdkkghgt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtdakgdhfh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtircbtgox.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvbbsufv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtinijdeqr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsqqfkbr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttqhcqpjo.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gthhnmqxot.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gthujsuzsu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtszpekbgc.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtgahfhmlr.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfazlehwc.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtzqvsowwu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqgzcjnd.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtxztkmwii.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gtifpffpzk.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtflytknfr.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtunpumfry.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtwgvtnzyu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjsxvoauq.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtswamuijk.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtxpgefgys.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtfnrzxebk.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtttyguqws.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtjqglcgxy.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtnrczapdo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gttpitulky.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtbkfromnz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtiugbgvfj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtzwrcmiij.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtbchcjcxn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtqbsczhxa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtatmhxjfq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gttcecggrv.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtlphyzrdx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtmhtvvuou.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsgzinwb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtbzpdfbpq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtwsomanld.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtmnsljchp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtgtfqvwpz.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtmvmnoarg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtwcctprlt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwfwwiisn.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gtoreeklhu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpacaxvug.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtotozvtzq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtytmgjhzz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtqxlgrvhp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtugcycrib.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gttqrpgutj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtypijsoqp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gtvicczjgh.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrowzjnww.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtaemqzcsi.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtozmqjurv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtpeesorwq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtbsurfkln.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkhnndzlb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdbdcihkj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtyejbejtd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtyhurxxja.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtjkysgkci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtxcordyzm.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtdadorynv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtklqcjhsa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtdwicndki.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtnjdzntgs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtqfgyvkld.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtaouhenqf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtgkaobnfc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtsdfstlfo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtjmgwygma.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtscpdgzfs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtlntiomhs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtinurcegl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtwefuxykb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtqwnczcet.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtuwajstbo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtkgmpgxfd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtbupqrqqn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtjfojjsgi.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gthawkuwvp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihukxlqv.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtziipkgqk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtxnfeofxu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtaznvriuj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtpzxmeilp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtihmkegaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxapryxk.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthghpmvcp.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gttpeuzlwn.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtabrqaaqn.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkhhxhwxo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtujyqtlzx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzqjkmcxq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtjopywolq.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtjtvmznni.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtfennomhh.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtfkroljve.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtsvutorwt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtwbdukasz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtmxfcchcz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtnjldpuiu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtejfpjnlq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtrylihhqu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtlktmxyuh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtxbkquhkf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtfpynjnmz.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtpcxwtldk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gtjuepywhr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gtracddbdv.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtfvuyobbm.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtlwjqoqkk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtpvgmxjko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtcunxuzbx.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtjqaelurr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtjhxnctln.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtrxrigipy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtsylfdndh.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtmklbvxwo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtcedxolbf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtgbjtmkpl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtmpozldln.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtwqhnntnl.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtfdrawldm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtwepghdkr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gteobpywsa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdgzkiulj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtnmngkzbw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gteuueauge.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtcglwemlf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtzicesaqe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwcvuhxpp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtcwpkwmya.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrcqwixys.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtnsnarpyk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtoffwkuav.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtusyaxzbz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxqixmbjl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtixylfpzd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtqzayrkll.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtwfuhqmsu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbiwkhhsg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtnhwbhual.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtcsusrwnm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtexvqclot.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtukqwrzij.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtwywzujqm.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtcghiopuz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gtyqupkigw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquojvwmo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtjjoynctx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtxqsontnc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfbqmzefk.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gttweqkjzn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdvcfcwfr.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtzykdpatw.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtbkjqparc.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtwlxanbpf.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtowqxzfhp.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtxufennkw.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtqnkrcedo.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtqkzyztwn.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtxwsejios.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtgbkchwuj.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdnelnsi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtunhnioej.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgkpdswpm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtuoeyvtla.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtdnvdzcpp.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtoeobquqw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtbwicczwc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxnlvvjxb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtqzoejgkh.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtdjjqvhkl.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtpkfppmfr.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtuklmgbvx.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtuadcwkym.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtrqzkgknt.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaseleuc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtevvlknem.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtetvhwsmp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtjiuutyyy.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtjbdwvbis.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtqtivnozi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gthelanfke.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttxnllghy.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtejtaoktr.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtjhyskdmw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtajzfctcs.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtgehkrhjy.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtsntbaiby.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtpzdekztj.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gthriacrpr.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzopnlrvr.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtznouxaku.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtjzuuvxda.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtgxmtgrdw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtmgzvgnjo.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtecgzfpyb.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtedsqdons.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtvkfkugvq.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtrlvfpikk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gttzgwlwpz.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtjarhahon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtocjgdvvm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtvnqkcghb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqddkiyt.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtonyuetal.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtovvdlatk.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtxzrepdqh.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtxheoydrz.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtsotfmkpw.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtdjuxfzeo.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtcuorsqjd.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtzzdyrezu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtkezivvrd.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtiypvbmuj.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtyttpfrgd.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtmwzfbcvm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtbrrzpapo.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gtuczwbdkg.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejylyeja.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtbidpiude.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtojqygcpw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtkkjtproh.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtaqaiiefn.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtctkwhznj.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gtqvjqglvs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtpoohejwj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gthfncpbnl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtqpaehuoj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtrwegshwa.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtewwycarj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtvukichzv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtsduvymmk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtcgfhyyhu.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfdrjpaa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtcyvxitsj.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcipvzkkj.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtvqwpntno.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtglfwjxez.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtemitrrzi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtaqsxpdub.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtvajzwkjz.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gttrzhsmjd.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtxvzyytud.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtbicaixtb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gttpsunahw.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtoohmvesj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwifwegmt.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtrgqpwasi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtwvnxpauh.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtsffmbbcq.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtjgbwgquf.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtmhkslcwt.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtgosxqpeo.html


<!-- 参考信息 -->