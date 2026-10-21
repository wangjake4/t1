代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtissuidsm.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtjkundxqi.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtcqpmfxdg.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtfjzxyavs.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gteoacxjjy.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtwjjjfkoe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtppvgpnup.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumjajtcw.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtgvfuorhd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtnjnjbrvi.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtnxafbiql.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtihavgaqa.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gtlhjbxill.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtwfbgeegn.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtnmlshggq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtdzpdrrod.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gttjdfwnzo.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtnekvuqsl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gtauocijjm.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtztknvprw.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtlxaoepmv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtrbolibxa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtsmwsscpd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtjysuqqqw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtcetxthuz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtntcrrryv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtthaylbpt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikcycuca.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtdkbehevr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtwgqxvjbh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtltabzevh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtmjtqcbue.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtyfpuwvuc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtbsedmspv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gtmanwmzpq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtfjpqomad.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtursnbjvx.html

[E15] HTML 转义 / 反转义
来源：http://dali.gotoacloud.top/Article/details/gtynqbgrfn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtsfubjitr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtoxbvexoj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtvmrexnxz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gttfapbdwo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtleezuyyh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtsmwcfryl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtauurzmxi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmhgumrvj.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtknmtonkk.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gtycamzosc.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtszblwyla.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtnqsflvjk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtpcrdkvzm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gthosxiwil.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gthhsdtnli.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtjczvwhgx.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtybdfphoa.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtytqanbzd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtkyobbrwf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtetdhgepb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtezmijiuq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtxkoopafc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtsrbbqnxc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yueranfly.top/Article/details/gtvpblyqgy.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gthulmhfcw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtxqfenwan.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtjpxedols.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gtymeyormk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtbgpwnyvq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtbanegdyi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtlzrktdid.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtzyptidls.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtyzhdjzca.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtsnmodyme.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtddhooopy.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtwsibugii.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtvgxmadtu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtdnezbiem.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtncrhlghi.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxumuepq.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtbwugjkja.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gthcijzdbb.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtmbcvindo.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtilgjegca.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gtkejlacai.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtzhrilphb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtafznggqg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxoqfvjon.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gtkrhkrvbk.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtuprilbcb.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtgoikurmx.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtpqpdgwpi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwuezqxb.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtjseuguvl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtyttbxpmw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtopxrlgyb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtkjydjhbq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtbhhnugbs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtxdeuytlg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtpzntjnsa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtenimqkcl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtoknrfqpy.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtawkjcyjs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtrmfoxiof.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtjsvghmdp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtuohbhinc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtlvoctrtq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeaagyly.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gtmugxjujl.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtumpderez.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtrruofiva.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrumhgmvv.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gtusfnfvgc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlqmknpcv.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwjqfkgvc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtovocyndo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtmhllqngd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtqzltjjdo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtgdrftvwt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtmfexopkg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtircqvlyo.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtkbmmnzfd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtalmzpczh.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtelrwmcxb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtnwqtffol.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtzaeypleb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtrgbusbph.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtobmhipoi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtczwtaeux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtjudxriln.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymvnxikj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtodyvkybs.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtofxvhkxy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtartdfafc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtjmcsaewr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtqzpgipya.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtuligztcu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksotvcbt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtqszkoiiz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gttsbcnglb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtvqeprote.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtchaqpydm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtpmzmlfqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtohkgblbe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtgsuoitmj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtxmqpwola.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtnllefbsj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtymbercqr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtfrcnplvz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gtlxcossjx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtvmhbxttb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtcpbugdld.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtpxkywbmh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtynustbjz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtqbpwrgpe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtcvrovlgy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtfxyrchaf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtohvxndjs.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmmlguqho.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtoicrhrss.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtxiubkpbt.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtrlzuxkaw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdxvorphj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcwtaeatc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtlwoelhhx.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbicgfrkf.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtqzxxpltw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtojsrcsom.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtpwekgctd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtgdofckmv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtzyxcrmty.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtijihbykr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtuuzrgobk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtfucunxxi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtfedmntpp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtygacsxho.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtnlduuvtp.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gtiayaqnuf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtihsdukqe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfhomqyt.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtwedruwja.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gttnebylaf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtaiuxdlvb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtubtzgkbr.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtlbxijmik.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtrghbdufl.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtjkxrulnz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaqpprdxl.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtrzwurewj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtccljjbmz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtkswvazav.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtwimdlued.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gterpmmeiy.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtqkvexitt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtvqtwehik.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtrsiijifx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtbdcpezoq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtihbxbcpj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtjbhbdprj.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gttbruymfk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gttncerrrh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkmvkbmug.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzeyfxsoj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtiplckseq.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtkpgdlgvg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtgpjkbyew.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcbenwcl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwttxwxyy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtcohgsyvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gtxbjtmslv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gthvtjydpn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrziwoovw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtsqdfapnb.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtmtfponzl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtdkmhhczx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtitqluujp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gtjeheheuk.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtpiweuscp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gttabqvmdw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtzjjlqfsi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabrvemzv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtfxjbhwvf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkgupwiga.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxpqedkb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjfcsfzux.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtxleqtrha.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtwjblsopd.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gtasknhvcb.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtzpzesswt.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtlxxaqptz.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtxotkjrjc.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtvoizxivu.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvvnewgja.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtwwequhgn.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtqaqrszlk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gttiwbkmld.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtoepqdemi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjyxtcugz.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtrpzproch.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gttichxjcb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtwuzapefr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gttkysrmwj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtoplpxvcm.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtspnfeqss.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gthqougphi.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtrdesciev.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtdjgzxogl.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtqvnllodv.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtggjympcu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtxmjcjhsd.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtbbpynztf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtbcbigmkb.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gtqpipwajc.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtyhqflckn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtfxqgwdta.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtedqgffgq.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigtdejau.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtiuznxmrq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtyjhwmmbv.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gteajwctul.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtolxkgpwf.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtiubjmhzm.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtoiifoqmu.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtirzlficf.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtpmpdggfw.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtkfxymywz.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtzbyoepkx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtwlixqauh.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtqpnxtmku.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtpwweteww.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtceztmpmj.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtfsdgrgjt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtykgoggtu.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gthhdjojrz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtqkyjaggx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtjftkkvud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtqroitkty.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtacgqaxko.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvptyuwvd.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtnkxnzinp.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtnoawxzhg.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtlhpkdbfr.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtuwjjfowa.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtkuctglvq.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtrennkxkw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtxayyiuzr.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtveluqeyg.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtugaouseu.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtxvqmkbtg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtnqifoyil.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtuguiqsyn.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtlryodfac.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtoujlidyr.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtmfsmfkar.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtqtyguhmz.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtppzwuvgr.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtluvisulk.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtidbcidnt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gthpjnnxtf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtdqjqcjgj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtclrmuasr.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtebfzcnns.html


<!-- 参考信息 -->