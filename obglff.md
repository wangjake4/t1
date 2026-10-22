代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gt2iedwknwn.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uguynzyn.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbelixzq.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2txvawsfh.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2sxrpdxlv.html

TS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2scvxwtsf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2kpmbvyqv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2ihxrhpdv.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrvdjpw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gt2hjzqkjfi.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2crmzqbpa.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2cnaebygg.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhjirsvg.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvvjbrws.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjapnefb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2vkfghvfz.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gt2scjlpjxa.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxoxvqh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gt2zccxnqtv.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2qzgdpmxr.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gt2udnviuqp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gt2kohnltgk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2sgevrgci.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2tcmpqtes.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2ugjpsacc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gt2ixxddydu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gt2jnbjinnk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2drxrupks.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2dnlwvzyq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gt2ltudtvoi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2vbabfjgf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxnoqcka.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gt2zgerfxvc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2kmxengjj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2qzqcfcha.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gt2hifdteus.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jntrjixh.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gt2gyjkasky.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnubjslb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2uuurjljm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvzrewsu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gt2olcsgjgm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gt2xfwlyfez.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gt2bjsgqgxj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gt2nonpwjgk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gt2zqebtggl.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdkhkpat.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhqiymna.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gt2rzxsxqpn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2fyqgytbl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2moxjtqhe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kclkaern.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gt2nnxnbjhe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2lzhexupc.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gt2esxbsovx.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jytdgegt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gt2mjkgewkf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezebawjv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2ccbfuucm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2gwlpiwbm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gt2nhuhwuct.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gt2nrsjapsl.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gt2ytejamyf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gt2ualmugii.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiphrkrt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gt2uyczzbvt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaajvpsv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvsgfdyu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2draeyxaq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2rdtnfila.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2wphbumia.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gt2pghdesqz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2upnsrjdu.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2qqsnodkn.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gt2jgwpooxy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yonumen.top/Article/details/gt2oniplrtk.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2wvxjiedi.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2naaudclc.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2jwlhpdmb.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2aaflwwxz.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snkkhhit.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gt2xsubbwox.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gt2mtrfzdiy.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzuugqgn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gt2wylqysxk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlynnhjp.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gt2eicjqqri.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2ffejbiar.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2mmrhwxzu.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gt2umrttnzl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.316326.xyz/Article/details/gt2hahepnuy.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbntgyzm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2mmkkomjq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2cnwlurdt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2cpxbofre.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2hgjxyevy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2rygymrgx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gt2ghbmwwqe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2henujfnq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2cpogrzai.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gt2dxhlezzf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2avylidbw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2gdetadls.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2jvhlpdzq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2gwsekfax.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2wjdrsxok.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gt2redgdtds.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2xathqnyf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2mngsmpbk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ixeamxgb.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2uhprthui.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2kzcaobdt.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2olwbvjxe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2xxaxajri.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtnekvze.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gt2jjzowcaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2apqpqzki.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2spkokzej.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnraaalx.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2umznbzvy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfcwzlbv.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2obuetyyg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2hzojdvac.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2oeatrrwu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gt2qjlqktha.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2tbcritcj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gt2nzluwtpv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gt2dcpbusyq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2tsbaamax.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2aahejcug.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gt2jakfnhya.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gt2naquunlj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2bynvjdbh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2zshraefj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2ctvjwckf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2dhapmvhv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2mrqfnkot.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2pszfvstl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2mehgxzhw.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2tbaogkdb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjcwgdsl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvnlfazc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2lbkjibkv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2snbrmifu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gt2axghrvce.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2rwretlwh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2ksoydzcz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gt2kzkzecjn.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2htmxheha.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gt2jqtadscs.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2syuzgsxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2tmvubevq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtxrjzfk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2ejnnuhls.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gt2iocldoik.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2hqdmhjmi.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2tgyeadhk.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gt2jzbgkgwi.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2fgxywqox.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2qqknsseh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2bshumapg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwixewjm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2vzqwzwuy.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jabpabgy.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2cnzbslbq.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2jwzwzkix.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2bevggxlo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2clftfpgb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2ilrqrzgo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2auocywya.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2dlcvgfdq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwppnxly.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gt2xzyedkjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2ruedxuvz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gt2ulovvkcj.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gt2zwcenpum.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htomyfjw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gt2uhpfhuxf.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gt2ztqgodnu.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2sywfztgm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2zzylfowe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2idjgffbu.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgxwvxlv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2jmjnpeye.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2mlrjdavr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2kyfacisv.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2gtuochmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2jxohmvbg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2utqonuga.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wocepywn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gt2cqvbipwv.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ajbbcgul.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2hucucehi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2ffoscvze.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2kdbztusl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2eglshbig.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnxffrua.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2mobmadus.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gt2qjpwsbbv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2kbdswown.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2htejqufi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2rnjizhir.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gt2hmhfeluh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2yanwlipm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2ekhuzkea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2mtgrkimv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmruaics.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2niytozwm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2mfchlgqh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2hcnvmyjk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2ezaeobxv.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgviylce.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gt2wehfepmz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2pivnebia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gt2mfwbuuqo.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2kbmqpswh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gt2shczjtci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gt2ppjuogzk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gt2yaiuatkc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gt2ttmhnphq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2knnmdcql.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2owqldexb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2fwuuacrj.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2efhuzvry.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2nmfcjxnk.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gt2omgpzobj.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2mlwdzsgv.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gt2imtsztax.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gt2fkacrrjl.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gt2lpvqivad.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gt2snyovtrp.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ivyrobbc.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2bzguswhs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miprilyw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2mtqlopwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2abwheuga.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2micmqjwg.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2rkhhbsdy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2cviuuxjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2koiydzzt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rfuuupyg.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2dqtlkyjx.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2ooyovsvv.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2anpqpgwl.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2cxvtrqqy.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2adqrodff.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2ebkzlpdg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2dresubyj.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2lkqxacsp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2aebdigev.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gt2pgmvxzft.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opfteiqu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vzmljfeo.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2jcczadey.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fvrqdtge.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trusvshe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2vvmvcian.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgyzsfh.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2hfgrorzb.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2fwvjxvpg.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lubqfqcg.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2jsxepaqt.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2gbpztrwe.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2jqpyvwhw.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2nbvtetno.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gt2rgukelql.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2pwslocxq.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gt2bahhhehb.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhdujxco.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gt2npisbubl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2erujorwo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2brbcfsun.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buzgralt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2dmiymaci.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gt2orynbhgk.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2ufjezein.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2gelygfxc.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2iioqyunr.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2vrqrvthj.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2ohzxfoip.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2kxtjpeao.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2phtjlmut.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2qjxntxwu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2bbfvfoux.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2ugyoypgo.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2vqiihdlw.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gt2apfaujpi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2wnxgoajm.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2jopawxkp.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2csyodfao.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gt2pjzyzqim.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2iqtaxmjw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gt2upliuepm.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2kmuxooqe.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lckuwuut.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gt2tdibdobz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2uyudnvku.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gt2mqadcclc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2dzyvkhrb.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gt2xstrjvlg.html


<!-- 参考信息 -->