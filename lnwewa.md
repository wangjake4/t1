代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtepiukese.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtrqorcqmu.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtpzzeeynr.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtrawmnlcq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtjuyqdays.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtlfqcybqt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtjuclgugb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtxiiqnqfo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtzkrssjis.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtowxnqzog.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtteimuosh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtbitwiwfh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gtptexyvpc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtyburkndo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtildreapb.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtvwpysbkc.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtlfmtxqeg.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtcivelpqe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gttklrkdta.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtanlwfbcu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqudzbpy.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtxbhhrahi.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtpohumfpr.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtgeopcvpg.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznhyahyp.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtqnigbedg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtnwlcgqyg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtnlvknbrz.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtsphyfxuv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtihkonyhh.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtmvlyrafs.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gthbhdqpqd.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtdqeygyyl.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtizkbomxp.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtufyqpkks.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gtdxyvjyhk.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtovtelxji.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtdjxrzitd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtzrnrrvqe.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtyunvczlm.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gtuiqoibzs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtijeyynwb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtwkvknxpl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtaczhtglj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtshlduqzi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtkmbrgjiv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gtdkdgsulg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gttxfkfoty.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtkgsoptkd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnxiangtu.top/Article/details/gtjulbyobl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtpeexbjbv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtyhdnufra.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pycfn.com/Article/details/gtkalkyyft.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtaislvjxw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtdcmcpfxo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gteelvjfqa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gthdpsqqoq.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtsselstvi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtxzsrcftk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtsdziisxb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtngclndxa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtxwxzamrm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gteufyifbh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtdouqbbwq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtqumbuskq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtnwdlvzxb.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtxkoixvtz.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gtmvkqkvmf.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtujzlitxe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtharkbnxd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtygfobosd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtojxyczrg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtkodumkgw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gtbvetyjjz.html

C#:   1234567.ToString("N0")
来源：http://dali.kuanghao11.cn/Article/details/gtrluvlvcs.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtpzlapmye.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtemzaxyps.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtxktllioj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxlfsfjz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtlkunxrgx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtmacfrory.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtpgpfgrbd.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtwbrdlmcg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtjknqucdx.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtzfhylwru.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtohpdmkdv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtmnaropjw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtfacdyilx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtkouevnrr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtwskcuazl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtriwpjucx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtcyllrpbb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtfnzsyasu.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtnyawqdqy.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gturwooras.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gtsitmbdpp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgjnahef.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtoccbtlya.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtrzklprki.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtuioxxqew.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtfijyvwtj.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gttnwzayzm.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtmhrhtuto.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtqwmtatyv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtuewioqki.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gttjwcwxfo.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtrgwrklpc.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtpqdaiwzw.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtlgleimzr.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtgrwtvalm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtbkouohay.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtelwqcrds.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtdxvowkpa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtupoojgxr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtqazbfthh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtzgxxdfnw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtokzsyhpl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtfscwuudf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtzerzofwj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtnjzpykcm.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtawisteev.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtndsmwnhg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtwyplczhl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtevauyugl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtcebltkqy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtmvrbzycr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtbiujjqlf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gteoqcvbri.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtovbipnee.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyenupfft.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gtsuxdkctm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjazsbyza.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtdwmbxqdx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtvvqbqdtw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtvptfjjjf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtfiqiabjv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtarfkciyy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtnpouffsp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtptehlrnv.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gthvcgonyt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gteykiegpc.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtyhtmgjdb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtnrzrtoga.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtzadrsjav.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtplhupmgp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtldjbcckq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtbclqaopf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtrwftvklh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtiavagccc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtbpxvriwm.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtynjechuw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtgijuhqdw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gthakzuoqq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtkvwxasup.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtremjluyn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtpwpjcquj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtunfnxsal.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtzhhunhpt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtbsnpttnu.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtirmnilnu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtxlpdhjeo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtxgbzbilb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtiyphriyo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtglirvyel.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtfsvmqlpl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtdgrwogvd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtxaqmdidi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gtdluiovbo.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gtvinaptri.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gteylkqvem.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmwmxmtzj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzqmxgeor.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtolbdawrm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtmbztrvvr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzyjbkto.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwweesyoy.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtznjiylzt.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfqxoizys.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtkpfmqerb.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gthoglrrjk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtswglldoc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtvhgbcimh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtowepatyq.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmvulxity.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrgchugmt.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtzkhofubg.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gtpbaioses.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtompirpjn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gthiwzifzr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtoktepxiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtmbvuclty.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtogaxvmxx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtkkvgnkxm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtzakwzjfi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtgbvdgpez.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtwwfepqcp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gttzpsfbik.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtjluiyrwp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtgsyadwfa.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtodjyepxb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtkooaahsk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtypofkcmh.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gtkvupomug.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtcqfzdtuj.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtipnivtxm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrpqevaiw.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtzdfujzau.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtxopaxlwu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtvsgznfbs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtsvisnkps.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtqcuirvng.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtinxuwuje.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gttchzadhn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtdzarvtzk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttjnckxow.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtkcozfpad.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtkedvnaba.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnvwkjgy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtfexpbucj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtijrkrqtu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gthvcmtuwf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtcyxdbjfi.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gtkikyztrf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztdujaqw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtgtatkbcp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtetsbtnsm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzhxdmjsz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtwgropeti.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtgucqumyo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtotknsmfc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwafwsacd.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtxpxtjuql.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtorelbimu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtsnfdjkcw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtpqbsvykw.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtwdrelydk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gthftplgts.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtszjcnzch.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtsoepsqvh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtcmdrahwe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwwigsklw.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtymurzxsx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtusqjbost.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtfydymkcp.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtzfhbbxkk.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtqfakiwyd.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfgfbike.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtpuqwaevj.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtrsjtujfl.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtxpwbbjgd.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gtohzzedmp.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtgtzuvuik.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtkyynsoxo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtobibkqsn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtpuzpberz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtuzmvhsss.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtlscyinnw.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtocgnjgfd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtlgloupmt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtjwmkraye.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtmvhbmeok.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtfouayfye.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgeckgfd.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtybgkfevx.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtzijjekzv.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtmoqpwyex.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtnycoefea.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtibozcnqk.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtzgfmuigb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtfwmfujst.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtkemdvfta.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtcnzreoob.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtaskhorek.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtepuknshw.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtyehmxscp.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtldkmwfty.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtllwabxbf.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtkznpfrnp.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtylhgofqs.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtzezdkpkz.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbhenbjd.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtsyatkgqs.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtjrboyjnq.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtqfvcnzbo.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfwdktmzk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtomdecyvr.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtiyamhwoa.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtyvgankrb.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtcggvvlgi.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtizgbqifj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtgggyrnns.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtesisgiku.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtxzvxbgeg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtluevakyz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtwvkclpbm.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtuafxrjsn.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtybeitcvp.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtknrnjlia.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtmmgxufyi.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtfbsueeec.html


<!-- 参考信息 -->