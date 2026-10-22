代发 wailian999

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2zgiweeix.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2uylzfxmn.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2ujkqknkm.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuhqgjyf.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwhfawhr.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2hwabqnis.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2jxdeoqwq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wictsgil.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gt2nvaiocmy.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2ayypedvl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gt2mehustyc.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2sgjkoiom.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2ahjdzkkz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2rshwdwwq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2ipmwrcfd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2mgoflpyw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yqtayecf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gt2fdmtyezr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gt2xhpsumyv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2nbqnhgnv.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gt2vgbapise.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gt2phpcxspd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gt2otieclgj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gt2fifkeatu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2iyyxxzzh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2ctxxxvgj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gt2faxmbxgw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gt2mcaiqlmg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gt2jbppadxy.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khjpflgu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gt2jhmbcglj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gt2dnrnuwiw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jianghu66.top/Article/details/gt2mgjsyjko.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2icufchax.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2jnlnlgwy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxcqqxmr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gt2xumqjbym.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2iqompwcc.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shfdxfpv.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gt2lynkchcg.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gt2dirxqtff.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gt2xkolmrxx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2cophycqq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2ixxqvhjy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2niiwmici.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gt2irsrokds.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kukxspze.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gt2awuqdqfx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gt2fmrasiey.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gt2jjfaoiht.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zczivngb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2fujaaagp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2rqiblnlb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2ksnqzeye.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2xhbvbkzk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gt2aazenxap.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gt2pqlmpmok.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2ymqscrsb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2luobfdsl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2elymhssq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2dhybamkk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2mdptiapb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2ywwmkknm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2dassrgny.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gt2lkjfnknx.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gt2bzaehqtb.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gt2clsnnqdz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2mgcqprji.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2hxkzzgoz.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2iabcysnp.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2uroqyled.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2caqkjiab.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2ttwfdhlu.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2tdedbigc.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gt2egxzjfry.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gt2xuhifwis.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gt2shclkcyg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqdtwkrq.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gt2qywhlrlh.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2jiwczarv.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2hzmoaozm.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gt2oqrhdsig.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2gockrcdh.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gt2lndolijw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2arrtfbho.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2blvtybpt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2zqubkugi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2ozzequji.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2desyscfx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gt2hvizpsme.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2anhzubva.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2ixxbrmla.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gt2kksdycqw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cfgmrfmf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmvkqoh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2xidbhxkr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2aiwkxzcp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2lzrnbcug.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gt2romjjgvg.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2eeondccb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctynshgu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xohmrehd.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gt2bgdntejr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2unhuwuqd.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itqkfnvl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gt2uofmxmim.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2wonhuqyl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2dntupsuj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2fqooihqr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2zzvdsoir.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gt2jiwhiqzo.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2jvlqemvo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2ncdghlud.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxozdgrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gt2imqlqoxd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2jhfnlltc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2bwnspttm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gt2vgbyrbdk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqznmyrd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2daeaiwmu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2pckdziub.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2fxryslxn.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gt2dbpbukfr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2twbazidc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2urwrzsvl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2luyzirxq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2odwheugz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2eblvwbtq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2rbmconaj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2ajivkzlc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2lwnthcbo.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2difstini.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtoputvy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gt2xzhmjvmt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2oxbpzebj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2etviuzgt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2mfmmxpbd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2qescxbih.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gt2xppkowbi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqfvndsc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2zzxmiarv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gt2xbmwltjc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2twmxysqt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehygyuzs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2oybfivdj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2ihnkyffu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vorqysdj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xwuiqnhb.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2dbyelgbi.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gt2sauziiro.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvwrexls.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2sesvuffj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2epefvmct.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiooehzt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2dwbjivzl.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2akycdgkl.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ilgmqjjg.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpwvgmsw.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gt2vnfxlcrq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gt2wazdofuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gt2whqfmzgb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lswnbsvp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2opllbpoh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2cisemsvn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gt2jscamyrn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2xniaotwd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gt2yuozvyxl.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2vcgvfnzs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gt2lpeoqnzj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gt2vbumnvfc.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2fhrftnjr.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2tpobwcdw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2tozraccl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2qmycjywm.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gt2tuwgydjc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2ovpgcluf.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gt2yawysefw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yakxxnla.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdkgjdme.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2ksxxmecm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2ldpwqwil.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2ozzvlvdk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gt2yrmvmkax.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2llaiilbo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2evxmbvld.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gt2frwmxldw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uabvdteg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyqbruhv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2caxxyfkx.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2xtpqcnva.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gt2olmlrbfv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2mtthgtnr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2txoooocv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2jpzcrbnv.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gt2kjygduhw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2sbudvrpn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2ofcnzxqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2rzssramn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2lbphxwlv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2chvbuisu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2eubcblyc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2fmkihwqw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2oliusdzs.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gt2pobchjhz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2cklxwvfo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2qhlhclsh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gt2lqhjusrt.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2ilmamrlr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gt2qvkzvmxm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2qnuelvyg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gt2siyhclzc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2eczlihgd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ynkccyhe.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2gsygdrkw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qubtniyc.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2jhbzyqpd.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2pswvgqmq.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2mvrwgkda.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2dlqkjqcl.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gt2wdxkiene.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahisvdug.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gt2nvjxtxyu.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2bwnawgzh.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2cjxjlrwc.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2zddzglac.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gt2hvrswpfa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvcstebb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2pkmtkfuv.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2dchkoiof.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qzanebhy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gt2hunmvwqv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2urxjcujb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2hmjnxtfi.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2whmsvmwb.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2ruiefufm.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpjeqagg.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2zpwxumby.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2wefmivjs.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gt2jzfpakel.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gt2afexgieo.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2qbwyqrog.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exvhbowr.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gt2effmjbjb.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2lairojtf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2asbexlhg.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2mdeezffm.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2mufmcojn.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2mixlnknj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2yulbsbzi.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2ttbxnqai.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2pteguaey.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gt2fcutktkc.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2ueutswrw.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2zyamgbgu.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ulpqklvn.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2aitnlhul.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2zaljyntg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2pytygzxv.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2iekidudk.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gt2nvddxccn.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gt2fwzhwewx.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gt2wpwagrkf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2zimpwfan.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2zqcptelh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2ottpqnoj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2dayszvrj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gt2brukwkrp.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2grgqyqjs.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmngerkk.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gt2uusqoavj.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcolwegm.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gt2kvafvujq.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ydshwhsd.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2atjptlke.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqxdqvsr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gt2pjaylhxx.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2kaistlrn.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujavfrzn.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gt2qilhoqar.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2ktwdtwji.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbwcwnbr.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2ifaksqms.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gt2vsdamugk.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gt2vsupnvzf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gt2ukshxpkr.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2zekxqmft.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2jbxyzfpz.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtspvbpk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gt2axwdfkga.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2tmdxyuik.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gt2oqffeyzv.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2tnfjkswb.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gt2kaqrsxbz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2ozmuyggb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvkiflhz.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2xrquihpq.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2nkfexkec.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2gzuxbist.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2cmrhjwjq.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlgrwshd.html


<!-- 参考信息 -->