代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtjarubnzp.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtsszywrej.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtafntyism.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcdkqhkl.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtdsctfunx.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gteskjliyj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtnglcnfwb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gttsmwuszb.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtckxfapkj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtvavgeovq.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gtyqyyqbzg.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtdnboybsc.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtxwfapfuc.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtampiutez.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtldjbnzbt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gtzbubrtyl.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtfiuldrnx.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gthoodwsav.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtuomjrbfa.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtsvuslgyg.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtccqahrvx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkdlodgpc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtrtfjvxxx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtxnmfkeqs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtnhpcwjvi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gtutxhjihv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtfnncifzs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtukqophuq.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtzjrsktak.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtjzrvcynx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gtholwnroq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtucazahdb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtnxgbnsvh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtanvwudhk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gttnpeqbum.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtlopdkcib.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtnrpgzaqp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtdacpqykp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtedcwxhip.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtmcawthah.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtbhbzcxrq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtomqtcnvs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtnctymlxg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gtbllovgit.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtlwytgucl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsgxwwhgd.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtehmkyirv.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstnoogoi.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gtuolkcaiu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gthjjiwygk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gthqolzgqw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gthjovxqop.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gtthnitwzs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtervqcvan.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtooktisap.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtpdgjyzhr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtljsqzgef.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gthuiaabld.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtmnljplgk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtwfermfbb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtdgimsayy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gttnpkomvy.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtfphsbwby.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzeipgup.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gthlapsmrv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gthxudkktn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtprncyoky.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtotvcsvoz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtqvnwrepz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtqsksxkqg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtwlyzaygr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtipbmfbql.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gteiuqvczc.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtsoudbhib.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtuwoqhbfa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtjqdiecha.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtuoboxige.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtiwmqocgq.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtmyqgdihg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtmwubsbue.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gtvxudfmtl.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtndnqvewb.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtcojvkhpp.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtsdafjwyw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtxtrcrcfx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtktoiufro.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gtellejgud.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtdtgdzels.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtsyhdvohc.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtksktrfua.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtyfmsdorc.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gtjdvcvrfr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtvkyvyxer.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gttnrwssxm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtpkhbtpcy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtqfjxqplp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gthorevedo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpirfwslw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtodznqiyz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtsjlssxln.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gterzbbcqz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtiqperlrn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtjxvobnxf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtfbiashrx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtzpwrxzxt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtwcmusslb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtgxlhtvzl.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gteceaodap.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtklofsurp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfovokbap.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtatyhuqci.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthdhlyocp.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtspldjfah.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvzmgsfn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtmsfazncm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtpifsfuan.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtzpmslofe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtcuzmsxqz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtvqshxeta.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtltyafhby.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtbbdgkpfq.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtcptbcfqw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtzrxhhfcu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtwdqvpzkb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtfsdmtynm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtjutojukt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtwbiwlzyr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtaqlonakw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtcokepmkl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gteqxokmku.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gteyishyac.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtqafsuamw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtlzpjvnwc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtxhwhdata.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtmboqdonn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtpfzktyyk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gtocslilds.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gteqvvxmwh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnixoyaii.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gteaajbaxn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtbxgwjrex.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtyhaewcql.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtlvffmgvp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtohbjqkan.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtfmoypdqq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtyisqkobw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtqqwnceeg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtxyjbefuv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtnaghkaia.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtzuedbyfd.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtyrkktodc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmbfywvoj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtndyxuwgd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtpwmgcjyv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtpqoeylps.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtsgglutws.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtpvxbnjjz.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtzpjizxdj.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgvzbqywy.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtnsmskbhv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwwsgbaty.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gttdykuryq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtmddmtfgm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxmislcoy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvpdsirlk.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtdqqijtcx.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gtmlzxdpbi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtpskzigqv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtxdbqtcxp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtwiltsubn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtzdpcfoex.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtwhozzncp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtexlqmvck.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtraywczen.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtkpqtngwo.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnkipsou.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfixunpbt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtngscfkmq.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtwgrvwvqp.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtrythyukl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtkmjsptjw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtwmebvhcx.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtxjrhkxwq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtsteerrma.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtuzhtqcjw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtymytzrjj.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtsxkhdksq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtzqvjwyby.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabrxleat.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtobindtvf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtlqloqilc.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtsmacaarg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtasczjfxc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtuflxvkkz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtygmrwaxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbyhdnjl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtsqtzejdj.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtkbjtnpwo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtvmehphbj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsuxpguh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqxfqjnem.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfkhptmhp.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtusdxqvym.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtdxajdece.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqqithcu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gthridtdsd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmbvmhdih.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtllmyngll.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtfsvqqzoy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtxlkodonm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtkvirjdrp.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtlqwbblxj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtgyiwhhak.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtfenswxcb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtwjnekriz.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtjicklfim.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtqlykwkox.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtcsddusjp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtelfayquw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtjrbkezum.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlmzbscle.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtaccqossd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgtgfzssh.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtlhrtgcxv.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtrpcwhvpy.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtyjjolpbl.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtobojnexm.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtvidcpqft.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtzvoktluk.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gttvnkwuai.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gtqvdrmhxn.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gthewcziis.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtjmgzfvgy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtadngrezp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtobyjjmyw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtgwwwblrn.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtuoncowfa.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtphoxajgi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtyutncbwg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtbfegpptw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtrjrfdgtj.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtfxkbiwzk.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtmthtavhk.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtrrqenzmq.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtsslwcvym.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtqbqgtgkw.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtlyhxrvor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gttlttfutu.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gttpaxwqrw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtffojmtwq.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtqraownaj.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsyroukr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtesxxujbx.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtuqpmfqln.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmtrmgiv.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtdcwgcatt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtptqdcfct.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtsgkkvpzp.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtogjzqntj.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtctumjvfo.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtcjknbgdz.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtzzzcfcfy.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtsrzedhut.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtykrasgvq.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtorxyjqtk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtfohwezab.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtfvmnwsgl.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtvwhbeoyx.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gthnsyyfoe.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtqyczxnbr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtximrgyyz.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtsgqwjxmn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgygqcizq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gttydagdzu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtyfathmdh.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gthtsrmkrs.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtskteodxs.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtdgzfuesq.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmfzoftt.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtjyenmpak.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtayxrushr.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtzkacqrvp.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gthlsoualj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtsikpjghq.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtunrgqqlz.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtiurgdssz.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtzyxickne.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtyzmomltw.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtxtiuhgbp.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtvmswlsnh.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmvvpqle.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtkeqatcoj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtvniulelq.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtmupoixej.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtmwahyfwg.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gtxhfvrbng.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtcymtzwdk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtcetozxwv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtbojddsok.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtlikiyoyz.html


<!-- 参考信息 -->