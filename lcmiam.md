代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtyvmlukqv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtpohtusjq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtuvmxhglh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gttdretxiz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtfsvxpeig.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtzsalxdwl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gttsvxsltx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gttwtaycym.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gtddmmpvvp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtorrklwal.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvyxiupx.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtlhzyhvut.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtpayersjt.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtpmsaklgt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtxsrlzmdi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstkwbvxf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzfcnkep.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtxzdoczpr.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtojujkgdn.html

PHP:  strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtiyndolen.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtriuqddka.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtzlnbxcfi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gterviqasb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtaujykpfg.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtdtbifbpt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtzlzhwwvr.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtyngrztpm.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtwztixzll.html

PHP:  substr_count($s, "a");
来源：http://dali.feifeiyinyue.top/Article/details/gtsufqzzpk.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtlealtnwh.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gteslnxhbr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtrqvixalh.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gtzuaydtzg.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcepdbmch.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtcszfvamt.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gthyqdqaed.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtjhykwvdj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtaqfibzns.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtaabcijyw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtveoinmel.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtynyidwru.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtvnxpydoo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gttyhwvwls.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtlxjznnra.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gtdqkfydnx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtnjzzemxq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtgbcdvyjy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gtocqpbstf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpirhndgm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtxeuryzwf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtmlwppfaj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtqegqljyv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gteyqdoysi.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtyqvncuhr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzpcxdyy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtfusbclsr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtbhwnhzbq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gtgxssjgmp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlsqcego.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gtqewtwqma.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenzaomai.com/Article/details/gtujzvorzl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtqfweqhpa.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtlxhgxuqj.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtlrlxoqjp.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtdatsgavj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtryomczoi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtrtyxtpmc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtvrirbiyf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtcvrrelwc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtsudavxxo.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gtiyciaori.html

[E17] 首字母大写
来源：http://dali.shanyushiyangtech.top/Article/details/gtenxctnmp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtxamywckc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtrnqiooow.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtpklpnkcy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gthtatylqh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gtpezgksyy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtxozxngox.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtvkkssxle.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtfzvvwugu.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtmvltabna.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtzfarswio.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgeydoln.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtjrlnotwo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtytswueix.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtfljqoscl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtadmtqkne.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtjxftahtg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtsupwiiuy.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtbkczouwu.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtutxplsrc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtgjohgjji.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplummnqr.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gthtwieftt.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtqhlehanh.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gthurrcpgd.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtqvpadoao.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtcfqglbdx.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqmdclnz.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtcchbigkt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtbpoogswk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gturosdcla.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gtaaswdser.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdfvalciu.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtevtlorou.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gtrzdahhcc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtyfozscwq.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtzunddkck.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtpeqxyeuo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtsqzyyjyo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtvooxajof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtzhhlslrd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtwtztmjgi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtrdvgfblk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtlwshnjnv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gthfbqrfbi.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtytjkrwrh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpsnoevof.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtvvdwwack.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtomnybvvk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxidwdkrx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtpupmtzmv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gtoorhzpry.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtrbklnqrz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtjthgusbd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxezjspze.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtnfclyzxr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjguhzjnt.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtarfceiqm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtiqjhizzu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzjbjosne.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtazllepdo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtaqiejmpf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtqnvkjbqx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtamknkzdl.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzcfwtivw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtpunlccdh.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtjghjjved.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtgshbwcyp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtzvzgaluh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtwgmjxenv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtyvzlqwqm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtpzctkdvu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gtubewsciu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtdvjdchpe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtjioaetsy.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gttmqcrewn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtebvwvglh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtxwztkcmy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtgiprubyo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwnminui.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtlibcslum.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtwazeotum.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtavjztylf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtoxkhgvbq.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtfmeyedxf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtmfnmmqja.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtvcdfrpqs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivvffght.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtwlztwaqe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtkfhxdxzx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtqvtcsbtf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtdtqomuoj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gtmhcegecs.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtsbzjpauh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtltpqqfkn.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncjfcwjl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtichebmsq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthtmbvcoi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtmchgqlqd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtvjkfjwng.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkjscgjzj.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmywhokwr.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtqancyrts.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtchwrptlm.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtmrvvntjg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdmuuaznh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcpbbxqbq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtmkizowzg.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkmtzqwas.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtynkdxsqc.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpsluqgyy.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtsrnwrdcs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtkvakpadx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtwogvejbg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtkqcpphlm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsepzlbhp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegvbtxov.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtpcuckpfd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtbzhzkquk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtptilkaut.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtdacgfutr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtqbykmjkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtoxcyxdxb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtjcedvsso.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gteiqoqafp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtygpuyizg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtynvgrrgw.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gteoinvdbw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtqtfpedgx.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gthopskhal.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthhzjefkj.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtemmmqtjk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gthsnulqkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtwsuqetnh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtcmsceaix.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtinkoqgys.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtnudxtpfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtnetyieic.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtcsapuvzu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcrompakx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwqbituxu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gturkmihti.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtcgjkvwep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtnmqwlmup.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzwoaowfz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtyjctprxl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzxtrnkjh.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gthdvokwxr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtkhavialj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtvqlrihhv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtdjwqkoca.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtokdgruyf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtrgahrrlg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtmutpkigv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvjxcmvri.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtuqxinrus.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtlrxmelje.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtfdlsdnai.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtckesmbjm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtcijdnexa.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtjtlmfzrr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtrqotfesp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtgyqrtzlo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtarmhmguu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtkqhyrfhp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmeudiouh.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gttrlhitjq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxzhfecky.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtiogxuavi.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtmirdelpv.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtviphjmif.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtdgbwlltn.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gttowafbbk.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtdodsnwhx.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtxroruiix.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtojywovhk.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtjqvcxvzb.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtbcnywunv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtgwkzlxon.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtxhlpmupe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpmvlcdxv.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtmregvhmx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoehzmbhj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzswqavtp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtymloupqo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtcqjzzkos.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtjwsmsblg.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtowpneplz.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtifatfklj.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gttaqhshey.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtwpfsbnpg.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtvekgljxt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gteysdandl.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtcyqswfup.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtufoayknx.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtauyutipp.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhnmiyjv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtvbuhufso.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtnqkexeyp.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtdnedjtqh.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtsxumtmfd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gteupvfdvk.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtrutgjedz.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtnzgaxqjz.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtfymcrlyo.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtsphtjbxg.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtgmsudonv.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgyslydp.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtyulptejm.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gthlusyeap.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtxxwbgnfq.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtnzntznuj.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtyszmmndj.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtbrfzorkj.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtiwjvxsba.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtqidxvtmh.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtlbnkgoiy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtkeehgbzp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtopxxmqny.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtybdpqklf.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtoglcevtp.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtuvpjrsww.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtumkhyvnr.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtbxawtxzr.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroeaomtb.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gthhlkfkeg.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtfcxfcwxs.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtuezkedyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtsckzwuhc.html


<!-- 参考信息 -->