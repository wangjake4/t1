代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtpciitscz.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtzyhdfpav.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtufhgiqmu.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gttdqnaaeg.html

JS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtsritlbss.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtxcgokeyv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gtwslumcmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtiavpwuvz.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtaliewyzo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtahsczmlk.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtgvbgenbu.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtwdfcgzwj.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtazowzasq.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtblksezfy.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtnqhztowi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtbghbignd.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtajzoylzc.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtxnrwzjow.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtpqaqgkqp.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtkwlxjohx.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gtcngdvycs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtijsxksxp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtdtcwqasy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtesqucqvb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtkbdiykuw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtuwlthcec.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtrezobyvf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gttvertxqj.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtveshmnmp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtipqhetpf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gtedzxgtkk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtkbuxjbuk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gtykcmhkcd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtvkaxmnua.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtjcnysmlg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gtigeuorjp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtjeidcnly.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtuxqxqwde.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtmoqbquji.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtnljdokfj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gtjssqtfde.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtbdyuatak.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtuhndgqbo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtflacwwfh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtqevshyvv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtibibsjvg.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtoccxtsuw.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtlhlutdgh.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtyhiniqov.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtermuhmje.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtzjvwkpmo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtcunstuqw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtesnrjopu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtfbxiroih.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtdexpwjbr.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtomdsyoqt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gtwwexkwea.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gthzqtbzuy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtubusbdkm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtpgpsgjab.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtpwwdbwfu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtpqjrlgtt.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtjczfglpp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gtbyqbsduk.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gttyqrdotc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtmkljqhhx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtezbealoh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtkbnjcmui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtvsmgscpt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtjnyihgrs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtsvhuedzt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gtrtubjbsi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtfzacmmcx.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtnkmwciwg.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtvinkhuuq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtjqcsjlqy.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gttkfsywsw.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtvzykvmoe.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtxxvjmwvf.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtakgfggmn.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtgannlatl.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtfgyrafdg.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnirenpyb.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtafzlfkkz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gtdlrlzdvh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgweerdaf.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtanqgmblw.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtrnmmjhai.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtqzzusbve.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtbseohiyg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtsvqyhekv.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtfpqlcafd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtrzlxnogs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukrxuvjs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtmhqtilss.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtaswwqfsv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtzgzvrvdp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtnezpvapu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtuhmdaozv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtjguhqplb.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocrylhdy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtjhpkdckp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtbreczget.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtwagndymu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtxhystxso.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtnvwvswbp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gtcntpzdxd.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gtdrulvskn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtbnxvwqej.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvvdowuwz.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtevhrlsxq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmphfnvkr.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtmahofgof.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtsqsbaxwr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyffqvybl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtpbtssmfv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtzrjqilgy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtpycfqlmb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtagyytbzy.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtekhxdvgk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtojyfrlpw.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtscekqfkn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gttijppvmr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtdmzjrxcc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtrvkpydtg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtpshyvgug.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gterztylqx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtpoqdljen.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gtspfyjcup.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtbilqbrtb.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtqhdfkslc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtaqbwbswg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtupfubrxp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gticleewxd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtwzfiklrm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtyojslxep.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtiyjakkbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtjfdbwfgg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtqxvbcjwl.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gthrjsdmed.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtqalbcyxw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtgtdyrpfy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtxnczwnyi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtytqellro.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtljqkvzte.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtcifgcwhb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gthtoxswen.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtnvufdyym.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtfktdxbza.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gtmpavtxiv.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtrftqeeaa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtrskdmoxb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgyoosmkl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtypbviyfw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.mhx1999.top/Article/details/gtmhzqlsoy.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtefburccx.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzhfjwudz.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfaidygj.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzzcloct.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtrapokcwg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtuumkdqxh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfepprhck.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtqwkwriwa.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtfqzlqvyr.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtqsiphrhr.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtduvqjmey.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtyjudrezp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgprjuqbj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtvkqoampv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtndftzxlq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtxvjmttpu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtdlkohiwr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtmuzdusdc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtwnxyoijx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtiextxefg.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaupyxpf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtixhsupxo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtehaegnfd.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtvvwfxyre.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtxbuqyquk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtskcnqtvr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtwwpcnswg.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtswcjrgji.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gtkfvubmjd.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsfvgsou.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwztfmzkb.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtcueaeclh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtavdgbgib.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtbzkiqnpy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtseczrker.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gthpzggduv.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtckxhoskg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtiyblwlgm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtzrjglckv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtgatkptnj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtiajubtzi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwlobewak.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthciueqfp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtogftpkei.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtoumobcuc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkvngpnpa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgkahznyz.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtitytrywk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtiydoizxs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtexzvgqme.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtlzxrvsev.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtzhnqqsrr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gttjcwqboe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtcygzcwum.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtkiensapk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtesytmdzp.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gttajpiifh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtzbnrqdzt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gtkqqeypmg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtopellgfu.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gtsyexxcsp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gtvopmjfxn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gthjapnhrr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtwiqtenmk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtpaoqoquf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqsnayasb.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gttdykkalg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtynabehir.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtdaxzuelc.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gthrfrvjyp.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtbsxcbate.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gtbdnuheqp.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtsjtrnszm.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtsfrseljr.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gtflyqqswg.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtdrrtsnzo.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtgqznexkf.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gtpjcojhec.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtonwmokwb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtahjpablz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsqmnntl.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtdfzphuvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gteibwxmwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtcokfwetr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtnspebblr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtbenozpff.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtwcwzkhqe.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtqbooxknt.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtbbzbjmgf.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtcebmgofv.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtbpnmbfjj.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gthcrxnkxt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtipxnwfxd.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtmfmlpbpe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtjfhqbeab.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtfbhivdyu.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtucjufthf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkpqqglg.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtbbjvvoiv.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtganbatvp.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtofyqwicr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gteruzktnk.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtgbkcpxuj.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtcvmgbczh.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtmclgqlha.html

Py:   class Admin(User): pass
来源：http://dali.birdmap.top/Article/details/gtcqrhyeje.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtklyztmot.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtjoylsnjw.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtkoardpxc.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtjrlwxsgo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtwpgqorux.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtfecqapsv.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtyzsfeuhs.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtcrasssrc.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtffbtarwt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtxfiqmorg.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtmxykonqw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtgynhdago.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtkmtaabuq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtdlzwssqr.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtrfxzfjkd.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtlingpghp.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtdbqvmgpk.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtudyxylun.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtveqpgsut.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtnwgcqeyq.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtdbmsqvdc.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtzblfditk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqtuqipp.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtlrzesaoy.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtaaeazhpx.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtfciyjldm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtpxbqvmcm.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtgaikbsnk.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtfpkxoftc.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gttyourlnk.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtemgqkthb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtxonziqgk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtszyfkuyr.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtpaaaqjwq.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtshisyvuj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gttlitnxgm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtejqfxcbj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtkqbxiiqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtswiompch.html


<!-- 参考信息 -->