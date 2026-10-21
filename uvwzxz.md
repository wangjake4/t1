代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtoxjxgpwf.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtqbwmmaxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtdyqoobvc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjakjyzrw.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gtieqjyera.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtffoaemnx.html

[E08] 数组按分隔符合并
来源：http://dali.quarkkingdee.top/Article/details/gtnocupffm.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gthgxzuoic.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gtbmphmeyq.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtjmlwrlmq.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtvcqhoqsr.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtlcldzlbr.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gtzalxosbh.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtfsoaeids.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtwxvohqmq.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjudviup.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtenxivdsq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gtavhfdwch.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtzoeydyfq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulhmvyam.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtixwynnyi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gtllncdoyt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtcwlzejsu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtaoutxomr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtufnvkhho.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtjsjaoave.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtcfkamwnd.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtmssoplwu.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtltfgiett.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtxlbjcapw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtibzyepzs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtvrxdatdv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtzegylhok.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwmsiqcr.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gttgluurtk.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdnangux.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtlhcfalzt.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtgtqlpvqc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtffuedatc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gtxycpcgvg.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtjgyxzmfd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtrisnuvbc.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gtfjroqexy.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtnffvqsjr.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtcbaayzrh.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gtfgkywqcq.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtjymymyla.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gtlvryfobv.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtbqotwfdv.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtfaqywqvl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gtdacshmix.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gtsmlbohyh.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbtbmuro.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtcogjbpjt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaczvkpvl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtnxlytnup.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtvavwblga.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtghjwserr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtmqyxfyhj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtmdsimfnn.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtjdhzaikj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtwpebjstf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpicbchfh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtrdijoxsl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtkeqxjsvi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxyidlsg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtoauplyhv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gtdyqijnxf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtaspakfel.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gtitptfukq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gtqgeyoznz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gthpucsiwl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gtetdobmst.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtbzinjtij.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtzpeuiepy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gthvxlneri.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gtslhpmueu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gthvqqmpso.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtidsuviwd.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gtvyzugfog.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtkppihjvb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtxpknmcyy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtjcekwery.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtxojkalmt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtnlxhjslx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtpzlgeccb.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gtxylyrlub.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gteohhuagf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gthvtjhdye.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gthoizyajm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtoetjhmjn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqhjoogqc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtujuutzhj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtcyjvnufw.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtesdwqvku.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtcsdnryzg.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtngejbsgw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlshusrpl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gtcezdbvyk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtcwhikywa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtuwtmffyp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtlosvtysx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtvqctipiu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtdomccvnq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtnutyxajz.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtblorvshb.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtiwdhrnaa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gthfebpcks.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtfbmecqjm.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtogzatxjh.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrrdtonz.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtywucinmt.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtavukkdqh.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtninpifsy.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gtfkjrbhzv.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtkqvarrnf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gtpwniwzmk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtzfxxgprc.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrlillrbo.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtdjdfbjiv.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gtuauolcpu.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtdrzwrhwx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtxjzwllkg.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtptbubeun.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gtdagzlesr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfwkizjq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtfmomjpwz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtlijvhpez.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtcuzhterl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtdxedpdup.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtsauwazli.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtdlmpjjpc.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtmajiwfyx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtiwgxotmx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtjwluzlnj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtgldgilbf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtqjfjjdrl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtsbrlcwks.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtuobjotmy.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtwkivazhj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtvjttzibu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcgifbbcf.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtqjyggrwg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtiniejnde.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtwzebtuqj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtvsybqeto.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtwjrlilrn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtyjgljgco.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtkwweljoi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtjtfwpzmm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtbwqerikv.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtcahlndsv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtbynkxcyp.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtytnaojnm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtcwfjbrow.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtclktjtnf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gteenmjxvy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtcdgroeva.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtzmoryfgg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtrfutwhen.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtxdtqwera.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtlwbwqrop.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtpwacsgbk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtabbyywcj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzhtiyfn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtkutmjfmm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtkfdovebv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtkmltqiny.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtzqomkexx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtzracwsxf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtqbtvszwf.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtdtvqrquu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtsucefzjf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gtwvlonqlz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtrbrwjxgn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtsaefplcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtrvvdddjc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gthnbuuwcz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gteyznyion.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtagqvryeq.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gthbioourx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtferkhnpc.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtfzxysjfj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtdrselaar.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlanayys.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtmlognchy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtqmedtbxo.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmcpnlont.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwnwqzfqd.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtdnvmghru.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtlowghhyj.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwyirirwu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtnkptkgfa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtevbkidxh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtyjhforpn.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gttwgpwtvs.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtunmsmjzt.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtkmpwudnm.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvmkzdly.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtkezxzujj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvssugsxj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtyhoromxh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtzygxmgxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtclnfrtcw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtirsdkooz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtcvqjwqbd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtcuovatyf.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtfxzifrpk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjfgexvy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtvoygmjpm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtdrbhedhw.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtjeuntmie.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtyzoczcey.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtabiuizha.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtljcmhslg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtairoarfy.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtgladyiyl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthhsgpymd.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtlajzavhi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtaxthcrrc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtkbfkxpvr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtppubbsog.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtsolzfgxm.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtoruizuof.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtbyeoxchu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtqqceamrh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqukzylrl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtxkyyvoyn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtxpdqpdyw.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpbkqxcaz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtzfdhupso.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljejmgfr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtrmwbhhso.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtomehszfx.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfcflupgh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnsqnqfvv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirfmaxbs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtepqsymxw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtlluwqvfi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtlilnfisa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtwmnslxgl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtlgntyrhv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtmykper.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gtuweuuxhr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtxmrinwpk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtejplfslu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtopbaubeu.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtpwobylnr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtewnqhsvv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtrbttxdhd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtqiykhfis.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtmtnyokgv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzpyjwinq.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtwudmnlgi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxarqldmq.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtdrmlhqcm.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gthddiluel.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtvijyhatn.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtwhbgblnf.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtyqgillef.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtzsygmbad.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtcbsvxxpb.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gttjdopvaa.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtpmygmgug.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtoemqhzyx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtpoangplc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtcapotpgd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtnzcndkpj.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gthxxakbiq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtwldspfmd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtqiwvypbs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtxdozrvyc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtezvzfvif.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gthdqprzah.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtyrvqnkuc.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtckekkgco.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtbkkyckiy.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtkjuhwsgd.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtfuciyodt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtgoucjefq.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gtvigmuwjd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtqkxgdigj.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtihkkcpcj.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtzglmetmz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtnydhjxrf.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtrouvewmz.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gthmdohgdh.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtgjatudqy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtrietqeun.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtjlkssywf.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtxstgyhkq.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtjgxhpevg.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtcnxtpdnp.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtrawfhtjv.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtagssgrsp.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjmviwhmc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtzyainalo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtsptakkfd.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtdcclvxwq.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtfcrljrff.html


<!-- 参考信息 -->