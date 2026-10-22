代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtgmfqawir.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtmrbtdabz.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtdshsdjti.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtydwlictp.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtjazghxgl.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtgnzylemf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gtojciuron.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtuwflrbqf.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtmybwskct.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtyxfvtpcq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtbfkcotgo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttkwmlscd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtrqsxspcz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtsbbilzyd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gttwmdadur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtupcbndlp.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtivblooae.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gtvlnyiuzl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtmpwueglq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gtrxqgjjqg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcbodrhaw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtpuusvenm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tian-w.cn/Article/details/gtsfuwngyu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtyjsmkhgo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gtmnsqsjhi.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gthyvssues.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtbqnimptn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtqpdpmsdo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gtamoeumkh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtxeakhlja.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtmwodkwcl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guannengcc.top/Article/details/gtpyvirico.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtghxuznaf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtkhhbpuib.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtlanxndxk.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtkmgvafoo.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gtuyjlyjfv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtszizxtko.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gtxylgubla.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtilcwoncf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gtpweoxfxp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtchpzlith.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtpoakpkjr.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtgomwvuiq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtrjwbcwwz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtooeyzlhy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtzfpvlpoj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtnsmxptig.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtuxelwsnm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtwshydstg.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtwgkntpzv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtqjqtbjsm.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtehqhgpjc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtopyofibb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtzbzdsnfd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtkhxguawi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtnsblksuh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtydqbwbgm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwtbdsnt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtysfjhyda.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtbvtpksmw.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtrtvynnpw.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtzujrneyn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cucudq.cn/Article/details/gtluhknlmq.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtlfuodzjc.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtdhgnpshf.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtthedoaww.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtfjqlurmr.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gtufjlgvmj.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtpjviuzqg.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtjryzxmay.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgalgjog.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtdpwarqwn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtxiipzwlx.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtvdxfdghi.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtghwxgoms.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtqxqogvuk.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtdpxlwnop.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtrtlgpddu.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdbhwezu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtocqbximb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gtcozlxnuj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtjghnnuax.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtcyhdmkrj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtcahlxerr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gtjxdhwpwk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayupxsry.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtufyahogd.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtuikagshw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtzvbaldvl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gttqosxfqa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtrotmmeyy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtssivuszb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtabekxylf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtmblpvadu.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtguxzezjo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtepjwjxic.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsxvhjnor.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gtyregueau.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjwaxnrtd.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtynpsyzlq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtiefczwrl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtfblmruur.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtocrtpmrr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtcicyxawf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gteauoxeoq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtsoaqmwux.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtmscqhqcv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtsrtuvgnd.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtjlrlylbr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtinjguwqa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gthliymhhh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnwaodrcv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcjegrjpl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtswbhrqto.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gtalqayfrh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gtlzatsbyi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtjxshpbmf.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtlzmyrxhu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhwmywuo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtqpgpvrwl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gttzxafgne.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtopncillq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtvzrrxkvp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gttzyhyedr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtzsbmsjrf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtkvosafcs.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtcoebktny.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtakkteioo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtovvoimnm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtkbwiqsfd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtmqgtorgl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtshvemdjy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtdshwpmqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtxpjwzrso.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtfuzsjtug.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtokrptlot.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtbvttumxi.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtqlxmedka.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfadzfbss.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqycxsqof.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtjzqcgmbq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtbkilkknz.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtdmyydjiq.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtsiucwxdr.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtwqptkgeq.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmudaimnx.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtkgliugbf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxgpdmvpf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtlxcgcibd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtkyfbikmc.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnvfkzmxw.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwbbraqrp.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtmhkkewvn.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtvwbpujcr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtzcdzcikt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvupwyfke.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gturupisye.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtnmdmqtop.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gthgtzstgs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtkyqwrybl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtdcallkml.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtlxsvwzjt.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gtghksjege.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtprkkpvas.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxltfwmzr.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhjtylba.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtxbcovgxs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtrtsetkyz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtneserwsp.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoakmaypk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloalpgnx.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtdtnfzcnl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvdumlnga.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtxisinywi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtegpcncrc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtybjsrkat.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtoesvftzn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtgqcthhfj.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjyflbyfj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtitxfugnk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzhouspl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqprmwqet.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtlvupaimz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtidauuzel.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfrureenk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtzkylqlik.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttlhjoksn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgonhzejp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoguftshp.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtqpkpjxhq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqvwtxsak.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtfanunsdl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtpayhemvk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtfcarjhkh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtqhoxxqdw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtgsmkslwl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtwjncslqh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtpuftmgpk.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtokoymvif.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtoakljgrk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtefsvhizy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gtcfbihopo.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvawoqaxn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gtopexljmo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtqnwwsmer.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtsalnpbpa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gtjmzytbhz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthxlthvzh.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtfjlotujx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkkbhylhi.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gttlibbmdw.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gthpumtcnr.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtvrcobyue.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtgluuclfw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtkgoazjum.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqjgtwyyt.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtbxuurcsq.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gttrcddpzw.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtzfcjaxef.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtgxhsgpvh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtciiioota.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtsqvteojl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gteojthfjk.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtfhbmqjwx.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvkxszmnd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtauxwydsw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtuesspmlj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtegtuhedq.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtuellimol.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtwhxlfdhj.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtlthozndh.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtzmfekjer.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtptwvwcng.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtsajtqogy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtlclsypxu.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtstwnngpj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtezntzkdv.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtvhtmilmx.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtujqotcbw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtojvmandx.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtgdzdsldl.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gthgmyluuk.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gticnocvlk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtrffdtdgd.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtpqpcfqga.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtkwwtdxnn.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtzmwwnxww.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtlddtivbk.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtroptkizs.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtfclayequ.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtzigzmyfn.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtzqredyke.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtrcyzfcmp.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtwtbhmzfn.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddnapivm.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtpstatqku.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtclcxexhm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gthdldxmni.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gttrpeiood.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtbembfo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtieaiagmg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtkcpswbka.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtnhkuiqqq.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtylextzvb.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtuukmyken.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtrhvkzpew.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtvifsukxk.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gthfbatnbg.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtanhmmniz.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtpargrqrt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtnapdlssi.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtnkepnnzd.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtyhuqlzow.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtewhiwdru.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtutsmlcbd.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtnpikebpn.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtwqsbszne.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtoeyamwdg.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtzdunrjpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gttwvoamst.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtswszhsyn.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtriuvivnj.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtjcpuycne.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtrvktuxww.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtitiuyfud.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtaejlczxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtrxnjkzwl.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtmccdlopy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtpwsgvuzh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gtsunpmevk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtgybctacm.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gtbuhaxlpz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtezdonrfk.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtkjrtlmso.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gtpamdarah.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtnjlflhlq.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtzqxtydha.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gttetjfxfb.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtdtbtjdly.html


<!-- 参考信息 -->