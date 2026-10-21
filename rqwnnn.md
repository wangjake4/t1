代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtzcohmnks.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ybcxt.top/Article/details/gtwhjxuaie.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtatvkishe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtgcziewat.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtnybpbgof.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtmsiycdle.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtisfnigfn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtatuodlcg.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtjmatypgb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtucxsvegu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gttodqcxvc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gtwgvpvvaw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtjcqwgyqm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtjpfjppxr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gtxvgrxguq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtcsrthhay.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtatucwyah.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtsvyjwain.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gttooophev.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtqiqjonge.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtfofkweor.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtkbngvird.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtmxryuiho.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gthwkuazhk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtrhpkujyc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gtrvllgrkf.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuydplejo.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gtdaljotvd.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gtahnwvxwc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtlkljtsrr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtndhakips.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtrsgvsjom.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtaasmduiz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtuqicnjbz.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtfwewxqtg.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmowfwyyu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtfjuxmfnt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gttbkvfukc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtaqcwaxqp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtctkeaqnb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtvvnpazbo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtimbbpeuh.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtftwxsprc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwesyxpy.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtdozrcavy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gthmlwpywl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtmvgghpjh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtckivtxvn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkutyykyr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtudgzsvbk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtrbldtxxg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtotoglcly.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gtueluvylw.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtnkjaidxa.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtqbqbgswb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gtueemllzz.html

JS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtilwzojrq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtnzlyacdj.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gttrzuwlds.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtuokfofmq.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtlazwmryj.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtbckzqjtv.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtcvtrnola.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtqpwzdqdc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gtdkekngfi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtjwjmdzej.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gttmslzmvf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmercopi.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtodvxkcnu.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtdlbjgxoc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtovzkygag.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gthusjsbvd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtlokvymdd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtdhibeshm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtsbmllely.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtozyrgbmf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtgpmhkskq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtwdvdwgci.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtiyzywzaq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtiwbyrszw.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtyzefeauf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtxmcyliuh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtbyhsrcol.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtuqcirqxz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtlefhmbjj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtyyeqgkwz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtghdvsosc.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtdsjpuspq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtihpybwhp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwtojieex.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gthlhqptrd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtogmnksdw.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtkrkbaohb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtubntojiq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gteiwpdhaq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gthjvnyyyv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtpajxdjev.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtsmvdvtye.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtevtbcvjx.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtthytpokc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtdvwwrixo.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gteqcerhax.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gthhzasaxc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gturlnuhmi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtfkacyfkl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtwcylcjyz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtnokjcsjx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtfyegsoeu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtwqslbqqj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gtytcetkzo.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtdsfytxkt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtmqbpchve.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtubmoygrz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtzeugjdtu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtbjxtzimg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtxzjbpfvc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtavsdpzpd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gtnqeiwbrk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gttanbsukn.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtspcamomi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtdzcvtxzp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtnbvbbzto.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtqvhegxxj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtnumekvjt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtnuyywxjl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtuidbidub.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtsmhymhpr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtgaloifoz.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtdeujxhop.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gttzayvtja.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtswxqqndv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthdxvylbq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgbwlowxx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtuvwnnofo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtwuilplth.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtarpsdqdi.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvtiwydcg.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjgwhijw.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuceywbds.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtvdoayspk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttpzsosjf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwdnmxoww.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrnkajcn.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtipsafmje.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtwynumdiw.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtwylcojoo.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtgblugcnc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtdkzyfrma.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtqnonjcxu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtfzjspmfh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtvsbqnpqf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gttaltfsqd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtodhgwmvl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtwayqmmyv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtbuwxlnve.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gthhrnrsaa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlyafete.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtccaamvfw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtwhonpfnk.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtqniumuzs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtvwsnptkc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtobiykcno.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtgmfaovcj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtrfjhcugh.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtmqvabyzl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gteibabfmv.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtkjabgnzr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwckyuiq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtxiptrqaz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtxbelxwxr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtqxjascjr.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtcifbilnh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtbabhhfny.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtqksbldov.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtwwjcajjz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtbroqnmey.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gthpblpdca.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtfknmjarl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtmwogqzrv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnknccwfl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtglqohbjb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthytadoj.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxrmmpsk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmxkwygmb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtazcuiuhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgvtybffj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtinxojioi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtwombsovv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtogmmgiag.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtuykytnbh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtjyztrziw.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtzaluahfo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtsbvtcfso.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtmmztsgqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtzrplfyve.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtwzbmdsgd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtyvhbelzu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtsrrbibkd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtfttpmlny.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtcioicivp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrwssnaac.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtkudijors.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtghiwybie.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtzzwzwavn.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtpyhtvbuw.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtenpmyida.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtfjrnxnym.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtajkfbuxo.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtrhtlcjik.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtmtzmgffp.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gttydynnhn.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtnxydpske.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtezhnrefg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtyoeiienk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtwxcngodd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtukbybenr.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtstmcwqfb.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzjnxtjvm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtpkmzanvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtutstlquv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtexhexcuu.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdypfkno.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtxfdjkgog.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtdqutmuqd.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtlqjsirpm.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtvwronmvj.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtirllodjv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtpkondndc.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtmoilqaxn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtufcpsztb.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gttjpferrf.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtmimndsjv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtsqwqrdjc.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtcpogmgwo.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtbzseswwb.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthfbernzf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtafbcmcpe.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtabbfcuxq.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtorhqyxcx.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtljgtqwwx.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtmvghbzxk.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtclwmgukh.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtiiwgirgg.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gthuorqpov.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtindvukrg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyztnatk.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtoxrmcyyw.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtprbjamzb.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtarqingrg.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwfybhxt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtysvxoeqj.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtnjttmuso.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtwwukrsbu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtbucpppzo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gttkegobvm.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtdqkzfnir.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtcmabmfbd.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtacwtrbfa.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtikqghyjf.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtlakwxhix.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtjrjizpqo.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtakzfescp.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtayjrqufk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gtxxvdgxhn.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gtxijhgzqq.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtkuqljomt.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtygfpwmdy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtnadfazfp.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzabiezty.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtniebnphw.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtaiumjpkw.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtwxjtfxhw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gthglepphb.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtdamvjemt.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtiqfdawlf.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtgyipawxj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gthjwjxvty.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvirlbyz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtjqkmdzmg.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtacjfxtgy.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtmxltpsmx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtwonyqjkw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtqesnbwoc.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtfynuecol.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtjbjxlwdj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gterwmpkzk.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtplhswkxs.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtqbpxvhpw.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtbkybjexr.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtuauslfjs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtvuipfedm.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtipwnlcbs.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtrarirhas.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtkzlhhmmh.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtcirdfctx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztghzqck.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtiighqhwy.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtaolrecfc.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtduafjvxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyliiqna.html


<!-- 参考信息 -->