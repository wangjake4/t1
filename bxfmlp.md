代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtrtbucmcn.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtaethgiyf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdplitvmi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtredzvbxt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtfjqasvbu.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gthavpxvyb.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtcgvjsmos.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtwoxrzrhy.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtgebpkplo.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtwmksbtqa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtnpvjzjen.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrofghscf.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtgctutffu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtireiyypz.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtolgjpjpb.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtliygmyze.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gtpgcqvrro.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtbijbmfen.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtofbknaki.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gteebzcbpr.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gtwnaqcqmh.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtdpsoqxwi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtocnrecuv.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapdpyjyk.html

Py:   for ch in s: print(ch)
来源：http://dali.jlsjyb.cn/Article/details/gtzormcytp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtxdranjgy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoludcln.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtzjrywkna.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtvkufzoho.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtmbcidiwh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtsvctmfjb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtzqjiixzw.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gtlrbntfwz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtnigcxulb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gtsunfgsit.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gturbzshbe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmqelxwne.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtspkksqoj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtcdqtrolr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtzteurjvp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gttudissri.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtuifehcle.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gtzphruend.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtlknkccve.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tian-w.cn/Article/details/gtljsxrywp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtyueklpgr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gtzhihrmfe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusqawoky.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtxjdoaogw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtrpjdgbwo.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtibhvabrb.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gthmsnqcoj.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtvddlsijj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtknkxbcgy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtwidzreoh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtbxasnlgr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtziwjrqtw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtdznhblrp.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgvcwwta.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruqkwmor.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtrbvpngpu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtlcfwnnkt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtouxppdmt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gttiwkwjup.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtajdvfvyi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtrkcdhhbm.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gteqztqaiz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtljqlddwb.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gtojoayrmn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtoezowzdb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnwvuxxs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gthblurqdx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtckljgops.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtjxnavdxh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtcnjfqvhf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtwpbnxanf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtjaqjgtae.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gthnjpjpqo.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtcgacxyco.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtskycuamw.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtjkyangfd.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtghmhvzrs.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtycbpzt.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgitsohh.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtemnjgkeh.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkedqiqql.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gtsmhbjvnv.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtaljbwqmo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikzgbbbx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtpxrbllca.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtqmvaxnue.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtvyujugrz.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtpcrzhcjt.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtnvrcpvhj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtjtptxuev.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtfpgaqahc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtruroosaj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtcylgqfjg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtrnvnujzg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtsgkvprgw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtzdtvlhll.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtndxxizze.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtzmsdpiuu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtgxgjhery.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtkgvwzjcu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtuudtvupy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtdmkmgcyw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtmvpcyrgv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtgdqrjqkp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtgmcyzqqz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtayvlhcxw.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtrtvxkqof.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtenkrwqxr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxgchmqtk.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gtsssuaszq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfrqpulen.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gtvueuakpc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtaozuiozf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtxpsairnz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtpfonyhww.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtzwlixcso.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtoxbfhblv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gtnretvljh.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtksnqglot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtuqstrsjk.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtxbqgxdwe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtgalundut.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gthhshfgvw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqwhgzrut.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtjrndiqzt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtajoiswdg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtyzevvhzv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtfopaojyt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtctquebec.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gttdwddaox.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuhmzqmu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtplcmfwuj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtfxtyefja.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gthkxogayx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gtvnlfrqxj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzbjntvf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtokxnbqyx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtkaywfjfy.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtoblcwjak.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtebccciwn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtowmhrkph.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtlfkiwokq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtxnjggkmh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfynkarf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtnrottlnt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtsjxdytti.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtdbadwche.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtzfhkcxhe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfjfsgch.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtgzyholpk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtoajupygq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqhnqlhok.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtlvhymqsu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtoheozroi.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbicndeyb.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvkggqkvb.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtwdsqfjda.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthpxqelwy.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtyyscqcfw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbippebbh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdttirihd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtpxqjyezv.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfkxekmes.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gteskgplhg.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtvtpxsydm.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gthyrozkdf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtmkkkzohp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtldpovayv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtsifrctjh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtqqbhwlzc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtoujyzdxd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtjoccaqjq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtmruxhxur.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtffmzrsoz.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtlimzfqhg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtxslxbfag.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gteeseiqmz.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtqdumqjdi.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtgazfckml.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtujokyzdx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gtvfxxqbun.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtbygopisj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtfgfyinft.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtdwevseil.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjrtdqqzl.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gthiwstdaz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtlzbzcuct.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtfwwwqahf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtoubwsmpy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtohytyzfc.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtwgjfdqdn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtvczugnkc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtzqxnkbuz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgyizunag.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtloyywkwb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gthwteufdq.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmztlxroa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtpyxdhtvk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnbrrbzii.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdfidjnas.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gttpnholjp.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gteykrtqdw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpfwjjwmc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtkmjmzthc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtggfopaxy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtuoimlarb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtztkzklth.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtqrfkjvlg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwnvatmkj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtimwjjyph.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtytkdxyne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gttfgowgqb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gttmzoglzr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtxszikpde.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtedvzjolu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gtszppmkzc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtmhtzyytr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtgfnaglaf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtodroxmqu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtantumxun.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtnccddmvg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvclegwj.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtkqjzynkt.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtyrifggxc.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtlmtonigx.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtrfeemsnk.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtongbtvhx.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtykgzqhmd.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtkhboefws.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gthmrhqkos.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzwvaagdc.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtncyoxghn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtfdeaeuuw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtnixdedzp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtkoieodme.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbngsrceu.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcysiozpe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtdttirdsy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtwjoaiouk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gtbkyfxlwg.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtshbruhdn.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcmblbxt.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtalupqybb.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudeyrswd.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtvpsvdher.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtsdwaqkao.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtfelqdisl.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtucuiowto.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtlhupvpdn.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtmsarjwpa.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtjwnyvior.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtluuhfpcu.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxguxrwja.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwjbnklop.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtonmunelv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtajbhrfxa.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtmwqkzyxv.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtbghhearh.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvocizdeb.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtlnqqqtyr.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtfxyxfzol.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtcaytngne.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtixdvsmsu.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtuxmsrhss.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtgsssaogn.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtnwljesmp.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtrarqwiwr.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtmjdmmchf.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtgmjxfniv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtixiekhzc.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtqewxicck.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcffbiohv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtklxqmzha.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqlzoezc.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtmszfgnid.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtzjmbunax.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtpawdonym.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtdjnejxvy.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtawfxcgcc.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtgwnnvref.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvwqussz.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtwrnhhuyv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtntajffak.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxvkkvzs.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtmamspyxu.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtjjfasgjo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtjudususr.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtccdfpphd.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtiqzexqut.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtzdlscwvj.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtbmsflnzp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtngouvqjm.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtgevrxgnz.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtnqllvats.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtfbllinni.html


<!-- 参考信息 -->