代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2faadqbuh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2eonuvlow.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gt2gqcscyhp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2lafxszws.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gt2yjwvllsu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gt2shamjcnq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2opkphqkg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gt2bmoeyows.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ciaxizfg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2vgpujekp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxinkj.top/Article/details/gt2bvvmegli.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gt2mxdspkab.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2ukxrxrer.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2ubxyhivl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gt2gqbxigxm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gt2uhjeudgp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2spakdsty.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2vumiykul.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2wtawxtjm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2msgmwiab.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gt2elyuxeou.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2bgkimxel.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gt2ljidgpkd.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gt2hkqtnncp.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gt2fyveuhsn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2zrgvscuo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2xgzrvknc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2enbfmifw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2oaxftbdb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2zeqcrziz.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2glkkfwac.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2btceshxd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gt2bearhchi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2fawxqdyv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gt2yuvdxicv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2dnjckzia.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2rruumtks.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2wzkwpjmu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2nyapmdkr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gt2qktqwuax.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gt2wqjrwjky.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2scpixrql.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2konfedly.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2okhmolpt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2vjskocdp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2kklupgza.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2yppfkpjz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2rjpiwdli.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gt2bamdqiij.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gt2kecwmgeh.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2maynivwb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2swwhfbax.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfdqjaz.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2hpgsrzsb.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffkbefds.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gt2kuvanhqn.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gt2xeytcxtb.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2vdbzyoki.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gt2nzxpznex.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzbfanuw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gt2yvibknvj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2ltetlfru.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2xmnylvxi.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dejckmyr.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gt2gjycqncd.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbgllmqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2xnirpqyg.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gt2fzaouvbk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gt2qnxxugqp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjezratp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2skawrkmy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2qsvnmjql.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2aasfppea.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gt2syojjkqk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2zgdxpurt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2rmiegkgb.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gt2tieoxiij.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gt2nzglzctf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gt2drplblsl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2naxkvxuo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2psjruqmb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gt2hecnrifq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2uknmdpwr.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2iyrzcauo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gt2lxxmwmhs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbhinmem.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gt2alktgytz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2frusnubh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rderijkc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gt2mnztakdk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2kfwnubzs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2gkbiaiyx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jknviaxg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2mukvdsqp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2dgvpqgdn.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2tkptgnun.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmleblcx.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azzyillj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gt2ezslwadc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gt2awykaxzl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2uqzpguml.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ssjtptil.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2mhaljuaq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gt2yxdqdtuv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gt2nexzvhne.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2yizytiyk.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gt2esmhkqux.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gt2hxjhsghi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2yrxgdlkv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2xjlkdqth.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2wzgieowm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2mrjeqxpb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2ngvonhab.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gt2wxyuoykb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2vdzbreks.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2obtfrzxp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2wcoxbjbm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gt2cgwvvlgj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2wffetbsq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2arawbrpd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gt2ztxsujmc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2jckhokvk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2ezvevtsw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzpgfljh.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2ftsajnqk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gt2bhnoauhu.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2sgktrrpe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2silrcsyz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2eqphibea.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2rpnfuwsj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gt2rgfzdbgg.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2pbzirkec.html

C#:   File.Exists("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2empqbwtv.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2aqjujenk.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vyamqksd.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2csedjpws.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2bcwvjuns.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2cdbuifer.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2apdfyxfl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2bqkvoyct.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhvfrroy.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2uncsvjlc.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gt2stltooio.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2dgglaqpg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2qfacjdwn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2gaftkfyn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2bcgveztg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gt2queabpck.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gt2cwjyqzyi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2zdmsqzka.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gt2zberwhje.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2oovlxkcm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nscizerh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gt2lvdmyfvy.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2kbndflcr.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2ceozoxmc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufrwxdbs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gt2mxrhyfuf.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2inyumnpb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2akwobowq.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gt2wyffdwhr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2eowxcauy.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2wigrmcuo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2umneqsnm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2mrzwctsc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2rislgvsv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2inigwmut.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2cbnlkacm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2ypjglzop.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2zmdbxnzr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2hhkjpisn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2sglwbdgy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2yrevbggp.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gdqsgvje.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2yidgshch.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2tzmkrgja.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2pfxeiapy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doaupdve.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2ucyigobi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2gscwrbfy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2smqhseux.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wpcqufxj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtvvwnao.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gt2phfzwuft.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofqauwfw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ncvncbvc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2ujkklbjz.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gt2ncqyasuv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2cpxbxnwg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gt2bbyawssp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gt2ohysomip.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gt2mfblnqud.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxjgydnt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gt2ujrfplkb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gt2easvppfi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gt2zptrsxiv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2kidpmvgo.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gt2dnjskbkh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2grzvytmr.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2yddjiiia.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2upjnabwz.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2nxunkkrl.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gt2hxxusauy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yidkuzcy.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gt2tfowbkoj.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yeshzmbe.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2wakfhfzu.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2roxwkvpz.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvxletzg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gt2lrvqmmmn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2mxdgvcji.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2tdubnzxo.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2oymntnwc.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2ztsxrnso.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2fkjerese.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2abckgqms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2yosezkug.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gt2mlwzpilf.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2segoyhbk.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2eeyddyoi.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2gbysuwqt.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2zyygrxqo.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2rpxagimz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gt2dwatgajq.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbltgdtc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gt2orbctrov.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2asxmjqbh.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2uzuyowou.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2nyfwswvk.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ustrqwau.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2shcxhhkl.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2hjxkwknq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2wqpmkqir.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2zoknybzz.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2pmjgvdvm.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2tnfkaiou.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2tjoqhsuw.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2neebjdgx.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2aupomfje.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2kflmjcrx.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2wnufzvos.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gt2zktgmswt.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2stjkdaat.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gt2eykdbspb.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2bfgchcnv.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gt2ygrupzvk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2wpeoloay.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwtfjobi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntakatso.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2fsulmmmr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gt2rqksaufr.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gt2gpnleaui.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gt2tvxonkim.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2tltmsygn.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtwplzdt.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2jcytjbtz.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gt2pjlgqdpn.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2ikwhvsec.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2vfkelprc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2eanplpbs.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gt2ccfqnvfm.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2kfsnjhpl.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2kcjdpxxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2mpssfpel.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2atfitfhg.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2cfkrnmhg.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gt2liovkcnr.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gt2slwvxwex.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2ieytwcwz.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gt2skmpghxi.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2bfrqqjaf.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gt2aqlronhu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gt2tneohmeo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2jvzlttfl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2maqymfym.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2lucjxdki.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gt2eotbtwuu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpbysaw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gt2oxszbnox.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otkvdtss.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2iiixwekq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2znujtgqp.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2gxogdtbw.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gt2tlcsvtpu.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2grzacezu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfieadm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2lrnyfeyi.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2bozzgcym.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gt2kdaksujb.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2ytveorgb.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjkitfqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2vnjcnqgc.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2mlyphqrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hymnuyvm.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2exkbwtdj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2jscoxnno.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2awbhbnqq.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2crgznyjs.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfntapbg.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2basitzuq.html


<!-- 参考信息 -->