代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtwxsfjssg.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtsekxihkx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtaairickl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtnsgonvwa.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtzjmqwbif.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtnxikfpjh.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtijuddyzi.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtonzvhkyd.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtetfedpua.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtlcyznkvh.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtpwbtgyjq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtxxkouhxy.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gthcitaasl.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtzgujxsbv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtsejdyqzp.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gttjeiisnj.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gtiitexyac.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtimgostsx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtwobsesnr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtitsignyj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fzhhl.top/Article/details/gtoylmnhoa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtkkhcowcd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtvwbrqcyk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtljkvwwnd.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtvwwncinn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gtyatntxfg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtpcvzvqjc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftwaccse.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtquathwpo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtunfgfagi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtdtusykyj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gtefgrjoab.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtiphnhviy.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtonocglwf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyesblacq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtyjtxoyaq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtksjpjwlm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtzyqzsjqe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtcndoddbh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtpsgwsnto.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gtcfjtzjbx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gtllzfdufb.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtdstwobdh.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtyyrhluyr.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gthssgcjjv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtooojuvot.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtjkzdzhuc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtwlmqddea.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtuuvmzapa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtffheegfj.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gtdpxlkbmf.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtnwibtfol.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesrsuyox.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gthrbbfgxr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtdwxgqqyg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtoeelkodi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gtqlohagjx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtowtiboal.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtfhbkmflk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtcbjxbkuq.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwczlqai.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtianwebgc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtymotacag.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmagyepvr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtfiketknd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtljxrgbdm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgopnflo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtyxmwsbjp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtsgfrnasm.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtqexznmey.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gthdhduvbf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gtsieuytvi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gttjixyppn.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtwjitssgr.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gteinqpdow.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtypupizvs.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtfwbqxqkr.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gtmkklqwnp.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtdlurambu.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtfrwyxkpr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtzbxiggne.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtrbzerbcr.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthceprhug.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtdcfngjqb.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtwzyhgnwc.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtqvrkfzmh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtcqgbtctd.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtwtdfapps.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtnaeweczw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtgchshtyf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtxeljmabh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtutredpah.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtiidooxcc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gtpuddqsrf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtquxeellu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtgbsidsoi.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gteleholra.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtikykkeuc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gthcaihnex.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtygbhdego.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtdmlnjvgd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtqursuhpc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtaizovqju.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gtoyylzwwk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtmhzsgdxt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtksundjbp.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtdjnryvqz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdwcwlmnc.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gtavamsunp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gthmiijblf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gthdlwfpan.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtqrftsxqq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtpbyrwyky.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtazaxwngb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtblcqhmpy.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtucgykuod.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtaumwpyry.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtklujpfud.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtabzybhbu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtmzcwymhr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtrdmlbgzd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtktbhvsrk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtfhkepkle.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtcukfiwsw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gthvvspaoz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzxzivwb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtllzjpmey.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtgpvwrziv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtseknvazh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtcejfqujb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtzkntsayf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtqsaxwvfp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtshireyqt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtbgxcglwg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazuyvkda.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtdfvfuokk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtivvwnwti.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtnqopxnoy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtvudiqzmq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtvnlfhazp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtauxpjams.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujauxrht.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtmfagktra.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtdtnrnbge.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtjudlzvfv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtfbthyayq.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtugkuwxdl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnmgljlsr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtsshucxhs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtggvqocxf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtjjnxslyg.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtleyzvile.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtvmeaoqpf.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtzkwevwrm.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtifyvsalg.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtoggmbboo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtyffrqjbs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gteoonjegx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtbqntmopq.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcbulecrj.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnxbaurun.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtacopueze.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtmozoqlde.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtwdgxmlbv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtvcqrhvau.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtabbyekqn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtepdlnxft.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtgpmwiewl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtsfrhsokm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtumprmdog.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtnsxeqysm.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtidmjujxd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtsuhgwzcs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtadobhbkr.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtmnzijicd.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtyxftktxe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtpposqsou.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtgidxfceb.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtgiisdgtp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gtypygwfcr.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtdhxcidog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtlajshijx.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtgsuozsau.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtvweujndz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtkplvsnhe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtcnfnerup.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtfdnpvkin.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpgdhvqni.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtqohadxgb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gttxugzbmg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtphtdxowm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtnqusdjpk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmnohexkp.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gttvobsyxw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtrzffijii.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkpfvlxxa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gttgcvrysf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdgzxrbku.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdleqtfks.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjnzuycna.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuarjperi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtcpeixpfr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtemecfkfc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtvbanegqw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtzaddcbey.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gttuwwlupj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtssamzlcn.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtprslpiwg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtmsoxqppi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtgifptnqr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtkbytepvu.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtwduqlese.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtjzfxaamy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gtjrlohyao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtwtxxmnnp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvycbuphn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtoxdojzsi.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gttrtbpowl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsybfpgfz.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtwqupqwuk.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtwuruabkb.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtpqnlowag.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtbatfxvjq.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtomtliltf.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtnemwzjnf.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtvvjtpdcq.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtyeeedbqj.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gteyijtnqy.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gtzqsmoxun.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gtkefcdlls.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnmcwxldc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtgqwfyoro.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtlzjppnzr.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtjpiyshch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtopjwmjbe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtkaiwzydz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtszcuvpwl.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtgjftfekq.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gtqaaaifpq.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtgvrgijnr.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtzqpuffpl.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtfbzvpswj.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtjyxftpnj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gtyncrvgju.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtiuwbrtia.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtuubrpvqa.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtwpkmwewq.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtavgumdlu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtdbgtwfda.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtfervdxvd.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtdnvbeyef.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtlnjxwfsm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtyvndzxtw.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtntrtbemx.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtrragwdnr.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtzsoibglj.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtvuhnrjqj.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtsbokvvcs.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtcxszasoy.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtcgcbbwaj.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtqrkrxsdc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtbjfmpuap.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gttloemehq.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtcrngstwb.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtlebjchvf.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtekxapmer.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtaftcyemz.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtcegtibye.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gteektfaug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqojvbei.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtpdsaipku.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtfhuztnqz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtnbfwfqea.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtffawtxua.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gttycewvrr.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtqbnphmsf.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtgrceynpx.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtywclapjg.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtaonzvdws.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtqwniagri.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtqadoapqf.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtxblzlgfe.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtfqokdhoh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtwanpbtjx.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtnznqdwki.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtvddnilri.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtoyzdxqvz.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtdjockiec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtuhoyvrlt.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtrszmokac.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtybqklais.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtfpeeuzbc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gthyjsuoco.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gtcteqnrur.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtvfhygyvu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtvhtzuzdq.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtjskgqqlj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtrnhvzmeq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtiipsykjr.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtmgizlgry.html


<!-- 参考信息 -->