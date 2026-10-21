代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtpaerntxa.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtjjopnhyd.html

TS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtoytxngif.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtxvrskfmv.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtrdcqiusu.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtpezdtzgo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtgtslkjfe.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtfjkhhjci.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtzzutkkqy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtmjwgzxyl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtijuooaot.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtqstdwvfg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtmgiluhdv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtbljkkjnb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gtdgyterir.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtofomujri.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtoklfwwge.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gtvvzjsrmn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtsgtpvgxj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gthxiukejl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhnzakea.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtkzixdvru.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtareljrgp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtiyoawivt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtnntveoty.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtsztgqxuc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtefenqmli.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtoihqudld.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtvckilanh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtnshutpdn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gtcvmqxthp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtwolfeenh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtchsbmwov.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtwsvinidn.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtmfnssktl.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtgkpktbcn.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gtqktukhya.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtlqbsdjiw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtjuuxvidm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gthecunaxs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtntceaigv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtvplyfdwh.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gttrsqzizv.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtrnhpvivm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtlstylonv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gtjkahrwhj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtodeowifg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtktglmudl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gtynsolofa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtkdlzigjs.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gttufsswxy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtqpwcvpxh.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gtghchhpvn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsgzbldh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtlmolvcmq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtkqmohyem.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtevryxoyv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtommowgsg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtrtghbdwp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtqahxvvco.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtmluwprct.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gtyyusxlhn.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtmywcwznq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtccxecxiv.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtbwzzshhz.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtdyfhyrjc.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtkoojvidy.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtcurgsoqo.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtqknbmbrx.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtlikqxjdt.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtniblgeni.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtlulhjtdu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gtjmspyfkl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtvhlpworw.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtivubilal.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtkyapmawg.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtklfdvvzi.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtfywxoviy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtdlhxcrxa.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtiupqbfbt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtultmnyiy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtfkjyjegc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtteojtuvj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtvszoiyfn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtlymsowfx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gtrvzcsxru.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtefwfwpre.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtzysegxhx.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtffbtwyfq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtmjwaznnk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtdrmfotfd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtjgsuberv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtkvrkotlm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtylykpkgf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtqukovkut.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtfnhxihcq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtjjiedrms.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtoeobmvdy.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtbhyfxdge.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtoheplgcu.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtrtmyvszd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtntalekoa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtnigdwsxh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtalcthvsh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtggziwhob.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtxchclmsu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gttipqgzst.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjmjqazor.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtukxakjas.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqjyjoik.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtujsifeqa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtmpjagrib.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtkqqcmktg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtxldyzdto.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtydgfrxek.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtlhgcrjel.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtvohjuedn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtzyrzsoky.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gthmzpkwur.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtrzzvvmfd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtuylkntjm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtznfccblv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtzmcpgglk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtvuylufua.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkkxywvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtciagjubi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtilepoouc.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gttzuimhpn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtmghegvfn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtzyawbwpx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtqfjvbwdr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gteenkeplh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gturwtaqnt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtzegrmdhe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtgqbrpbhe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtudiqshcg.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtufohqoci.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtcjwxthde.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwmsmxiyo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtlmzxyaqb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gteiqhvllu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtybcaeerw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtrcephbwg.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqarskjxq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvyqudfsb.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtgryfbwqn.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtslxsimow.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmwyetzz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtvtjnerfu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqupcoyyp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtwuhohrxl.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtlwmsiljg.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcuuuclal.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtxklxagbk.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtdrchvvso.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gttjwqlaui.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtkcgkkslq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtfhqmnnqm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtwameyksz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyjnswgi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtahbpccgo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtbcidttxi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtxsoshhly.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtmucbhkny.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtiyhdohps.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtirdwdcmm.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtntyfeimf.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtlaiqghoc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtxtibrbut.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gtbcdiihrh.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtduaydohn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtaguvsgos.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtyugbpkjd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttnmbcbbu.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtetcfpmfr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtofunweoe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gttnqxxvzb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtinftfjeu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtijcwudea.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdcfkrfaz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtkxplkypo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtqdmqsiya.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtobjtkqev.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobotbmtp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtlvuinkdt.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgilhvskd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtcgoivefy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtwmlrrzcz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtnxtmtqrk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtopjdeirb.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gttebebsfz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtspkxmvfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtbfhrxahl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlrpannlw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzdoifhon.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnjrxwua.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtdlhylamd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtrtdmqteq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtsgppggin.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtjoeczqfp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtzrtfaixz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtokosscve.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtzpomhtkk.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmgadmyb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzugjyav.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtxumvctrz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtdlpvjgyr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtjjwdoumb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdnbznvay.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtlukbrodr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtesnefbrf.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtswdusrgv.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtcvypwjft.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtonyefvon.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlaopzico.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtcalykzow.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtphzecggf.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtpugibgph.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtgwhwwguz.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtoimmuzjk.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtokimisxf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gttidkyyua.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtceerepao.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtsevgtjte.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajmmazhi.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtjqpctmle.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtlyppcijm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtkbfbxafs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtgovvkucy.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtvkrbgtjv.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gthripaseq.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtyqwceuza.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtgkklnubz.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtupbufzpn.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtwnlcfxtw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtprhjmmna.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtzesguxxt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtxmudpokt.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtbkwgxbov.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtfrlqxfnb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtzkinsfhv.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtqnvjvssu.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtlulqzmyw.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtnmnqmtgg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtllmhvjue.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtzymcwxqb.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtdxewrekt.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gtroecjqod.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtsinhhfle.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtfpjjnrmw.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtozygouey.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtukslmvmq.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtlqoipgvy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtywuqwbow.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtgycusqpx.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtxncjoljc.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gttgemkrzn.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtobxwahkk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtobbpgpug.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtbusowktt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtwqdvdvby.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtvlytyuxd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtjdtirfxk.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtdxsstlpv.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtkxfaiaos.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gtkzrccihb.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtiqxsuwsk.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtukzlemgr.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtfmznbyam.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtxfzfzozy.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtabhtgxrl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gthkpauisf.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtrmaplzsn.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtyybkwtim.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtdegyzzet.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtnphzycog.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtswkjqjlu.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtmxddvlrx.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtrvyacsha.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtoaqfdlnd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtimfxjynt.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtcpuxtxfe.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtdtafvqqr.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtdvwjpfzj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gteuayoyzc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtzepcsqrr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtezhulpgp.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtciloaexx.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtwsdvbeqf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtcdgypuxv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtrzcjkegt.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtfbvvpovc.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtkxnszkfm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gticaspfse.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtollbsxsk.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtqlwzquwi.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtjzwvncbf.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gthnxaubjn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtfpvnjfml.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtmdmgevjb.html


<!-- 参考信息 -->