代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtrpaxsujp.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtjndctwuj.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gthxkgizlh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtxxhkakhx.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtfcfrlmor.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtuevtyibd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtbpdcnrrx.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtsvufgwsz.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtulnguvzp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtvqxdqzbq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtplduamks.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtkorxherk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtjkxvdejl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtsipycpto.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gtgaxlmezq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtpzewnpvz.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtnjchnzui.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtiwcawlnf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtuaevxzca.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gtgdgjbuxc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgsbzcvj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtmgsnrvaq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtmzhibgjv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtsrcyklmj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gtzovkpnil.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtqdemfsol.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.bjfxy.top/Article/details/gtghhxclxc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gteqzfnjot.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtathdqhhf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtbrufaxhp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gtefctsreb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gteavqwohu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtfcqgpokt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtxnantnfk.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtohvonemp.html

Py:   f"{1234567:,}"
来源：http://dali.fengsongda.top/Article/details/gtcdmphdwy.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtvgrkdpzx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtquhrumjq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtcqtkykbq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gtaabxjijd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtlqcbqodb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtcdndrksf.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gthfgprtkh.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtojbzacyl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtwrjytecc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gtdddzhndg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtgtaaxfbz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtgeotbsjb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtysayuind.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtebospflt.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtskghhzzz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtcigfotoa.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtuqiqrnov.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtmjzsmker.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtovwfjtjt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtasshdfzb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtzzxjkyps.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxcffkpr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwusxelmp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtnviezaat.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtgkgetwox.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtiwhsnlgf.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlliurrai.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtyghpczmv.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtjuatrspt.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtkgdguvrb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtixetmiel.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gteosmwqdl.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtwombgszr.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvgaxwgr.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtadwjbtap.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtwehxijak.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtqvupepku.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtitegswyr.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtpjyzgkfc.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gthugqnztq.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtbgsmlbew.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtkjarvwmy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtpmnnblwx.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtpvdidpej.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gtvowfgrds.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtlcalieni.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtelwsiwge.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtbengozsm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtautaclnd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtpstjkeid.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtcjnxwwjf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gthjkabjts.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtmstmlmmr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtdrzhunan.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtbbwqvjst.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtanzzsoks.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtjyoolbie.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtpeaygvng.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtithtwqqm.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpziplqhj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gtheyznwgj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdjjzzwjw.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtepmmxsnt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsehdkrcg.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtebyctkcc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtobptbcmp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfarxyowy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtxcjxwlhk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtnbawptqf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtyoafywya.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrmtlvjm.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtdeejujhc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtsapcoeky.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjvdjzorh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtteeqbggv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtestjktdr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtljwtzyjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtjlhtsswz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtqtssiqxr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gtjtdoietq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gtcoiwacma.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtwtauvhue.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gttgtmcxbv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gthwopjtju.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtnkldlpkk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtbejyemzy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtoqfnidqo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gtrwcextcn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gteejfeucb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtjobjgpji.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtvezqltsf.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtrnyptjqx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtispcvmlw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gtzfaqsuod.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtamnzxahc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtosqrrxnv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtegoaqpys.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtgakrnvbz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtzknkofuo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtndfaupxj.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtolaueiil.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtuwcmwvmb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtkdnrtump.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gthvzpcdjx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtlchrqzzw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtkdvhoodn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gtqmbpnrjj.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtrqviebre.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtflzclftw.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtnhxkhfac.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvfzklevt.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqijqfdg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthknggsli.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzgnpfelm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtfvsqfbzx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthknsfuyk.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthiwhfwui.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtahhsajfd.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtmmnqsnki.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtywucfbdd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtweqlgghm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtxjnnteix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtdarpuoed.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwccywoes.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gttqulltjs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtdqsjqldk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gttldeapib.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtxymdxgti.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtwfypttbo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtebvztmgo.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtdzrrzcic.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtthircuyw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtffrctmbn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtcvggqabr.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtgfmwndmo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtlssrjqoc.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtyhxlnwon.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttowhodjk.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtqikxbsan.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtsolsbabn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtmxbsdvcf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtryldqwmc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtcudfmnzj.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtcywshkmj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtqurqosyd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtvjimglzp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbgahfuq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtsaewoqnj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtiiwfbfux.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gticgtjcmx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gtqblvrhmk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtomgwazln.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyseblqfx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtisulmppt.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtcmkkacum.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfizelxax.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtfgvhdjqr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtaujcoook.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtixwzvejn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtqwnrguhw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtvaoieqam.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtbapdnhrw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtdmyqpgrp.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtwpulgjls.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gtqbccvmwc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtyexvmavy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtflgojrgm.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gthypkubfp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtelbcmoml.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtrphssdbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtmjrjzhlm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtmevpetgr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqfeyqhqr.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gteubqkjpr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgjwdvzv.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtidcuthze.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtacjvzjgh.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtgcxohhpn.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtefdivoeh.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtynedxiho.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtqzqylxdm.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtideyfsgs.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtdsiyxsks.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtwldupfkg.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjvouhgwd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtycjulzxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtbzfwwltb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpoobznua.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwklylwlu.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gthvnvyzxv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gttueuqnwa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gthenhkyuj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gtneuovyfa.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtpmhjrsqu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtdxrfboup.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtacnekklw.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtthklicve.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtappqnidk.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtiuijlqet.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtuzdyyyud.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gttdzybbxa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gtcglfoqwi.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtkdkwfthp.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtahojeryy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gttndqqzke.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtmhxxspbf.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtaxeycqek.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtbkgibwse.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gttwepisnp.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtzcadapbj.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtpsgawuwd.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gterwulbkr.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtxiztckxh.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtabtswgaf.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtlehafifb.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtynfplphn.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtsltgutro.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtpfwahcsk.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuimwxnxe.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtxsgnwwlj.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtcxdrtcgj.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtcdnadhsb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtbnbfunii.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtptrslrxj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtclxyctyf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtoshzsiui.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtguexyeuc.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtnbikmfmi.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtultpiovz.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtkerdabuh.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtwqslhnqd.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtdxgjokoc.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtojlcfuql.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtrozxsilx.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtioesrfdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtsddirqlg.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gthomcxvqp.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtvipbgrtn.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtdybuhpri.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtrruzxtrw.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtrjtmdgwy.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtymtikzth.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtwrjibezj.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgseletpu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtvkuktove.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtkbdnpvmm.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtzzmrgivk.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gtebbwzimk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtndngapdc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtdswzxgxe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gteitkvwjb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtcnxtqcuz.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtvhaehhls.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gtkuqvimwl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtzsjsoqhf.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtwtgsjoyu.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtnjciymon.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gthtjttdko.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtmeqocayq.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtbclnrryl.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtvdtnwrke.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtcmmqpbgc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtichbbjgh.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtxzjqvlyp.html


<!-- 参考信息 -->