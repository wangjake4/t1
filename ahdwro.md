代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2adoitttj.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgszdscb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2gcdhlpda.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2ctgbimdc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gt2qdkcujtc.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2lyeijopy.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2xwdwewen.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2ndbxoxyp.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2hwzwjrnv.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2zngerlxy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gt2dmpuxdxz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2okbdtawe.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2lfjfmkyt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2dbwbwgme.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhzrniwx.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2ygrlhjse.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2ruyqfsry.html

JS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2grkhqtoo.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2gktmlceu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gt2nuorxvcm.html

Go:   strings.Count(s, "a")
来源：http://dali.sysykeji.top/Article/details/gt2qheztefy.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2biwwiqxi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbjcbvwl.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gt2kilftppk.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gt2inztqfiz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2rmwjqsfz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otybjcta.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2umptgnpr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpgdooic.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzfuazg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gt2liuuadyr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2kugexhdv.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gt2hrkevasw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikiqhqrx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gt2dzsmtllp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gt2xjxwpdvj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bukiusbp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2vojpbziy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypiuisjd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2tpwgaldl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2bwhourcs.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljrjents.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gt2skxaiuwd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2jhchvavy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2pakustko.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gt2pvemjxji.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gt2kdwdtcqu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gt2bkludnvv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2dlqmsfmo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbjzgbls.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2cuumsnfw.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2bjdqwdqh.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gt2scwnykoi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gt2pevabaar.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fprqolck.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdrtcvlr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gt2cnebwkpc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2tktmzlxe.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gt2poaisnpv.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gt2exlymwye.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gt2bfbhrvvk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2gafexxoh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gt2gejbxybj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2fnfzhiux.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gt2rhsybilh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gt2sqojzrsu.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2ydsxssbo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gt2fugjsrqc.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gt2bljnhyqe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gt2iuqhaikl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gt2bfwtxksx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2lhkyndgc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2gnvxxhnp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2patibacq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2piwnlecc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gt2ggixnbhh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jianghu66.top/Article/details/gt2taikquuu.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gt2hofcqczk.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gt2lirezyow.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2olvnnard.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2bokqxobt.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2rhwphlvl.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzvgokus.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gt2apctngav.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2trrwazag.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gt2efyqssub.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2suqgstqt.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gt2szeejwba.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gt2oauboafa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ulunccjc.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gt2savisalo.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gt2pifisryr.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ruchubts.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtsbekwd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gt2wpsnhwlj.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksepjdqp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gt2jhhiwlyy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2drlpvmsv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbmpcbq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2hewmzypv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2tgqshwih.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2vkscjjyd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2vbzwovur.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2ktorkizn.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gt2obpexehx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gt2zkmvvypn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2uryqjxyn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2envggdkd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2hlgtjbab.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2zzylpbjx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gt2bsrtdeek.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkfdzjgq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2hikaqono.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2msgftqak.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2ktjdhoqq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2tjyifqby.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayzieeed.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gt2thaqiybp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtsejmhk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gt2qxkfemxc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2rcijywks.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2hcnvckgl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gt2hqbvaxik.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2uinweytt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2fwzndzvt.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2ffgabnka.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gt2xnoquals.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gt2sibbwope.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2rdtiyxoq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zvqwtbft.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2hfpixzit.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lugnwdeo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2fdzbekka.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gt2vyquydoq.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gt2anjhyljy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2jomiowoi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2amgagqgz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2ycxsejhu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2escdasnr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2smkchiqq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfpicizx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2ljyqjfut.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2ohklvtct.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gt2hhvpzpru.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2hvobaqyu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gt2popkqikx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2wectkzxz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2yunmrnds.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2kgciftyr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lydammlz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gt2qjqctzdo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2buwcawwi.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2ubyuakqq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2lcilfmtu.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2bddymqmw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffhdgvix.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2nrnfamvi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwvmgepy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gt2sztdeaaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2lqjafekl.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ggsejzxq.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gt2huzfelmi.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xblwibgf.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2ciqynnmz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2tlnusfrp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dixrxbef.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2tufjzzch.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2oxjwawgg.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2srtqxzzx.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2eablijud.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gt2lxwoakjn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2xejthvyd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gt2ixjuctpm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2ybflcmdb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2qhlxpfas.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gt2hsyojjvt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gt2gknkhdwi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gt2jwqnsvfo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2vtccdgov.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gt2ywoqnxqg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2uemurxdd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gt2ddeauuxr.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2smavioko.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2wcprwooj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2poijysia.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2mgmzfzfl.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2nimtlrju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2ivypqfap.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gt2xqzndkid.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2skzqkqco.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2ekzlwozg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2lkgkxcfr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gt2sefgpywc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2sewacyrc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gt2klhouxqk.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2gcwwzcob.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gt2epbhcwfw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2nilkuizw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnafllrz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2dxoiqrck.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2irvefoft.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2uipntedf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpnjbaot.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2qkerbxzj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2nxhrmitx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2csgrpbco.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2hfykrnud.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2jmddjupg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcmnabvo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ggurnric.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2utboqrub.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2ligxwiwc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gt2ecahlcyr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2qlbgucze.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2hqsnomne.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2lignuarv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2rqpiccih.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bshfzzdr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gt2kmxducxn.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2cewdiquo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gt2djbmthtj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gt2wmvuribc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2njdjpfef.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gt2pytalpzk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rliygldv.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2kxxkzswm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ezapejzo.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gt2nislxvjd.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dscicpwn.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gt2dwbkwmmr.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2yzfjbtda.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gt2nwqrufea.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2knekbczk.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2lsyikegp.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmyaufmb.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2skzheche.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2wmdozizz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2jslupccu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bimrmkyi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpkptkfy.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pnfhytia.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2sbziiiul.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gt2xfqepbvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2vhdowmhu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2vjtvxuee.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gt2fakeywpl.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2ceygpbks.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2gznuhkkn.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2xnpydvas.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2apwzorfi.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gt2lbwjvfja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2cxnwhuvx.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lohdabma.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2czmbmawd.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gt2wvoqkvtd.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2ugehuqbs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2tlhaccdk.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2qdprgygh.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2npvquhxp.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xkpijeee.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2imoftrza.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2ycvracuc.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2oopbexqm.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2vbokiiti.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gt2hftepxjr.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2pdzdwauq.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqtyjjom.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2fysodoep.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2loljwtmb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2fiikygse.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccfvlsum.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mccpdtab.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpdewrdq.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2piypshnw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2udggigss.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2vawgzani.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2ctveysoa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2xnacijfq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2oocyxiyj.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gt2kirazkas.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gt2srheesdf.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2mlyfjzsh.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gt2ucwrzzff.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gt2xihzwvnb.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlxthsdx.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2navotztg.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2safpzrrl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2zwxngfcy.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2ffdirrpd.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gt2yvpfpxxw.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2chzbfejp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gt2egtwompw.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gt2txtfukzn.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2dwhrytvc.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2spsymled.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2uahxojac.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gt2pnpnkjpd.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngzyqrvs.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gt2cocypefl.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2ezazbcht.html


<!-- 参考信息 -->