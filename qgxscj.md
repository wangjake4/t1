代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtbntloxcd.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtkvdxok.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gtsgjhosxe.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtfulhxbvy.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtibibukqq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtwcxjjqmk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtrfwbzwmc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gthrfhejna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtchcijbiq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtbiavsmfe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtucxbafjo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtrhaoxyvf.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtojynhktp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gteidhwbxp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtmtgclxqp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtrlkdnasg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gthbgkwsaj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtlxjudxvj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbokarvi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtkknoucyr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtpghmazue.html

[E15] HTML 转义 / 反转义
来源：http://dali.yanxiufei.cn/Article/details/gtmijevrwa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dianchejie.cn/Article/details/gtewcpvvrg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtwuqmnodm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtfudvdmla.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtnmvvphxf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtrnczfjku.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtwjamoctx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtlvepjgzg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtmvirpfqw.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtvjazswqm.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtznlykpkb.html

PHP:  number_format(1234567);
来源：http://dali.shangyingyoupin.top/Article/details/gtsafpzsep.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtctoqfgpe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtxdwyixhr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrbaiomv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtdhdrzmyz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtwolsckec.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtqubxgiby.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtnsyxrnpl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtgcevnhzw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtrturxsni.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtlglhcuck.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtuszzedsp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtnrlsiwfo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gtrhgaezca.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtmosbfbjq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gtxrfpzpfo.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtjekyceph.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtrbgoyxdx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtlmjwyirt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtyolnhgcp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtngwdmnmz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtwfjoxqiq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yueranfly.top/Article/details/gthfzdelxk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtmtyakbsc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gtgykvzctm.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtxdsfrrdw.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtfmlcuwph.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtntyunqej.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtwmlloddu.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtyajeicqp.html

Java: s.lines().toList()
来源：http://dali.yueranfly.top/Article/details/gtnejeosgr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtvjfepomj.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtmbsfvgeq.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gtgznunqza.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtniuhficm.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtaebodybl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtdnydgohy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtuvrjqqgg.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gtfiiuacna.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtxxsykbmu.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gteqiybtqh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtdwifnlep.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtntrysmyq.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtrmxsqfud.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtbmwivxwn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtwuhaeppv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtniwglbnx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeoimjax.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtlnuskwku.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtxezlrcly.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtlqjpzfug.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtrwyhotiq.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gthljkcmkg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtgiujihuj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtjdelxatt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtpoeqftfu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwmwgfnt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gtofxnddbq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gtwylusvir.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtfippawph.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtmzoukkgm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsbzumbi.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gtlfjwbdrf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfoowynog.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtodzcnzlx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtguhchvec.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtkkszmkrr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtrzmhkocb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtsbpnqrty.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtvwqizzlf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtsqvijkzh.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpjgftvdx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtyrqcrqfo.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtrtscjwsc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gtrmsimxdz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyakqczma.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwymtxbg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtbpcsyjqb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtexvcfhsz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtoztfnwps.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtphefqbae.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtusvwiiou.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gttxfryuee.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtsrxomsdy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtkrqhsbgz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtkvwcnrdz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtrcrufwgz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtrqovdatv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtzxyhkoqx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtswormkir.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtbmqydcsh.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtxfdmhimk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtrktokihr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtuilebrfr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtlikyhouv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtsluoqchq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gthjhvatfb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtchqcffkr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtbmdptthq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtbmbrxzni.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtnjjzsegz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtinlftj.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtrcvjfvwx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtvfygpmuj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtkakoqtrl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtmyybzbnq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtacrezbql.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndozlptz.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtgsedpigb.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtayawofgl.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbsxkhlpt.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtcvlahcgu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthsjsnrgi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcobhrvtf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtvbpebubo.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtqgsspeub.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtwvusssob.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjujprdwt.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtaqhkbhgy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtkoeivrbc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtgrfyhuek.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtehamdalm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtbuzwzbhh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtiqqpslwp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gterjmeatc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtzngtmmyb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gttmhehqfn.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtepmukxsc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtmnrfibye.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtpltkutyc.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtesmvezlr.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gthazjlehh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtddhlfloe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gttuyseuuw.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtzyrfijah.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtvtiynmsk.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtshxlzlmu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gteqvvgqor.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtalvgstmw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtqoswwuqt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtxhpbevnq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtfzsqctvl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtlhqkxlls.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtevaaaxxm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtjkeascwm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtmnajxyxu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrphakqbp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwotcqldz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrubgrcmv.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqpenlygk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrdicaoo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqdhfscml.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtcqnyjsih.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtulbotzia.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtwokxgfra.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtuzsnkssv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtmfjskuhe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttizxxecr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtccnjnyst.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gthjxsbikx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtwvcjqhak.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfryjzptu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmisjsgfb.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtbodjwoaw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtkgtgqimw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtfoflsnoj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtqzpzksas.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtpovlsfiw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtqqhhlsje.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtlvfjpmxy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxewcgxgz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtcsmwmure.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtszftoism.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtczrkawgx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgcefdfcy.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtdecxugrh.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtaejhnjgu.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gttxmmstfk.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gttxjnrjva.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtrlqydqyk.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtdwbxacew.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtizjxnktk.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtxlawlepb.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtlwthohfr.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtykfxoyin.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtqklqbrej.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtslsantry.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtabsdcfhk.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtsiwjyojg.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtzjujyqla.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gtpcgvqmai.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gttjhbdecr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtameynwam.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtvnhkgrxf.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtmuagpvnt.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtbrbjjjqz.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtligmiwds.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gttxvyavmy.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtflbpmbig.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtrsbocrxe.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtwjrhyfgg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtbthfseuv.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gthqwtaily.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtzscgyqcj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtmzlkxtda.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtlhqouvuv.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtrvssnxzy.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtgfkisxql.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtnvsewkvy.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtigxgltel.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtqkwinnuf.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtitvfaadj.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtcothofti.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtkxkmptpb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtijmghtrd.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtxupvkgzn.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtccgxfado.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtmaqeyfxr.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtaikaaslk.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gthheclxbd.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtapubeqsl.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtfujldogw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gthzjchoyr.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtkhsqtepp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtbpafqcta.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtauogopvx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtblhajwsw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtsrlipwup.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtzvblszrr.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtprksnlkj.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtkuaaitxi.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtocjwnsmm.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtxfalqkre.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtljdpgaiw.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtalihyfnn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtjmbvmwso.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtlxqzoehs.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtbjqzljik.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtxthkuqnt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtcyytlknz.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtvxwqbmwy.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtxhkgkemf.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtdqjanafc.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtmkjqgqfk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtfeoucqkc.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gthecjqeca.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gtudumrftd.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcxqbuig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtsefnrcqp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtwqtzlyja.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtutmnljcu.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gtfgazzsif.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtqaadlixl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtowcqolnx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtnqopnzfh.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtfphostna.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtrnulivzd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtedpctczt.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtnwjoikkw.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuehqefej.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtywkaxtpz.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtxlowuecz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtqsgtktpb.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtssygmrkg.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtsgenbeag.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtntfidlvp.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaseeydko.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtdyiybyfv.html


<!-- 参考信息 -->