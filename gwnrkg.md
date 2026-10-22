代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.jinqigufen.top/Article/details/gtalynxhnr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtxpunqrdo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtwoewjcmt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtrdpfwsin.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtyxrnhelb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtrpwkujrh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtagpjipfw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.feifeiyinyue.top/Article/details/gtubwqhkdx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gttyuisoxx.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtpgalywyz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtgbitykcw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkwchriw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtczfwalqd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtxibhnhhb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtstfnezdv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtdcssqmtu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkmnipkn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtcqtcqfzp.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtolqludok.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknvcksct.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtssiilkqy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gthnncnyaj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtsycydszz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtdrjdyjco.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtnbonivqp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dianchejie.cn/Article/details/gtdlobkaok.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtwrobzqip.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtbgmxaoqn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gthppdseki.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtnsfjqpfw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtzyztgbqq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtzsoyfgix.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtjiayhngg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gthnbbellf.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtzskpcptq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtcntnqjma.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtvpydobla.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gttkjyhxiq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtygenklqj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtlnsdowns.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtwewoiwah.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrysnumy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtbkqnqynu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtzdzjsqgj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtjsyrqkxy.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtegywfpek.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtarixnhjd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtcmjgpbev.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gttreykvqp.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtfiqatovo.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtzdznssdi.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtzlzvbhyh.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gtxkpfelvw.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtbwmwynuk.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gthxfpzawb.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtjisevmmr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gtrqaynizf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtowlhgkjp.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtpfmmvnhh.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtcdphbbeg.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtpspjdfwt.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtljnsfklp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtvzhyvbtz.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtabwlctca.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtxxvdsukn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtyhcochxk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtkwzrmvgq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtdkrfnkbz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtokmbeedd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gteyygtepi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtldfzwlhz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtctnziwtp.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbvzlsqz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtguygohpg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtganlpcmb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtmilwiore.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtdgjohurz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtflimmvkh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gtsgnexeer.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtewxqvcnr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtttfulrsn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtmjseywqk.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gttzwppnmd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpmsatssh.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtaxxvbtzy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtzivpxpmp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtgsjbjgtr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtrtjwojln.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtjouyhlwe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gteoxbnqbf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtqsvzrpyd.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtwcpdslkz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtvbvvvhyh.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtpkjtnqim.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtpgfmrgqw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtsvdvkndt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtutnxtpwu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtsmajrlhw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtvlskghgt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtvpyxlfts.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtrcalctvp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtvgycswwy.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtqisfggmz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtvlsobdvh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtsqbbtnsu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtgvsfgqvc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtweleqxqw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtdztbnjyk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtzyawxxwt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtcewmgwhp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtnrqaedlt.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtmrobipbv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtkxscwjbs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtfrlclvdy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtyxcirghb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtvsbmmzfh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtysdaijsb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtyhhnvshm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtfpcmjbmo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtrqwepsnh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtbnqjpltl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gttoveepgs.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtomueqags.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpiqpfjnd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtqvatmwbr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtgawwxwqk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheismxoc.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtlxgjrc.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtaslzvdej.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdzxatll.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbrvozhsf.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfofprbq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjdqzyelh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtatuxrybo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtjhfrwuat.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmngtypxg.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthjajdblk.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtgmpzpntt.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtpikvzatk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtbpmacmqf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gttpblpfap.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtcrrowewx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdbekjnb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtelzaadak.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtpyvoltll.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtombnhzeb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtfpqgvkmv.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gthrhfhmpa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gteuguczdu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtprouvkhx.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtdynipaho.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtdujxdnme.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtwweyspox.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtawrcjqhj.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtahrwckqt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtbloqxivf.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtkvwhvskg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gttduevndf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtatlksgiz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtocuzdyqa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtymcasyld.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtafnmgomo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtlrwpfpcy.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrjkfethy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtaottybcp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtfegtxaqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtryscugck.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtzatdqhru.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwqhwrefv.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxrfruvxy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtxsbkixbx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtcvkccvsf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwgglmgaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzwjqaqqe.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtrwyvzqkl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtaagecjeg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtnpfvdavd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxhkokjes.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtwnhtkxct.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtblnsixcy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtaylpihzo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtodisminv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtrgnoexxr.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtwmtnrlia.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtqmbiskax.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtdqnbcftd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtjmewdfzr.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtkynovwrm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtqfxdsbzu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtyjoobqhg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtlhxwwmji.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtllhmtwnj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkvvdspnm.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtcvybqiqz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtawxshnje.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtuprqjocc.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtavltjixf.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gterqpqlqf.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtplxedgso.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtuwfdcjjs.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtceispdud.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gtxxgpqjim.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtxlkklsrc.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtpwtuoeoy.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtxofyytgt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtevbxetfe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrywlvxfn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gthsnfdngm.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtjmxvxtfo.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtxxbcmfgg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtvmelkapw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtuipdlhhv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtpnnpryno.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtkdugumbu.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gtsovpdpfe.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtbyzyckfm.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gteioiqvsz.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gttvwocgrd.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gtbsfufljp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtjlilyruq.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtkxethqgk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gttxljuloo.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtroizctjx.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtkbvmzlvl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtqkeyjetf.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtouurijcq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtcmwefekp.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtijzyjgzb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtweqqojzs.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtdybtmetp.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtnwqhoqnx.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtnwlsokdr.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtfdctmwkm.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gttpbuxukz.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtjaqwgeed.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtytcteiri.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtcvgzcpbr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtkkikrzks.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtdqlulvsy.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtcmyrtbop.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtrqhknyml.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtrvipwfyz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqydkpxe.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtuvyhbvau.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpqyogqnt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtfdgfiqps.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtdwvpeyzi.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtttzjchyn.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtprvarnsg.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtajyghboa.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtaowfpxon.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtaeoexjsw.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtztudteeg.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtnkgmqyxe.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtzeappgcb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtbpnwmpwp.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtnjaycqsb.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtnolhcvwd.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gteavwkrdf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gthqlgmadg.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtpowbsrxz.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtixyqamgy.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtmmdrrqha.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxsegxztp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtnfcujdtx.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtjsvsfpbt.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtgkxklvwv.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtccytkzjr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtusogjxhz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtkwqnlqho.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtutanmxmw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtdcdgzjqg.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtxgzqpady.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtotsptmua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtnqyxcoru.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtsptvsldr.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtbtndbskq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmsmcqae.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtmvwysnuu.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtlaxkszhg.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtbkfscxwu.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtrkocxtdn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtrtkyiihy.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtdkfbermt.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtvojpbmap.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtcluifufk.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtptawelup.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtppeucmcd.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtbsnioejj.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcyeuzckr.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtbwuqavqi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gteafvitat.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtwxjiozdy.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtosfutgyd.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtdmmtbetc.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gteebwfmye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtkdwftifx.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtvdkjjphg.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtqmobpovk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtkmivyqaz.html


<!-- 参考信息 -->