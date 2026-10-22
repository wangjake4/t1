代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtbatzltfs.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtetowtmbl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gtuwediwhj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtkxbftxgo.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtumwbbfgk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtwouffjve.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gtpzgbzcpd.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtuiifpxwp.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtdemnwgbp.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtwjcubyyr.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtuekzrqiu.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gttqgofgqc.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gtralrmznl.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtiicadcan.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtbrtbbodi.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtsveoxftb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtmthqluxa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gtxmdtnyds.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcdqkjhu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtdrngswvs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtgiceluck.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtksuaeqbh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazbciarb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gthvnsemxb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gthuhihpri.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtczvieoeg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtdcykzxes.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtokqawzon.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxmmmnbx.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtzxrklpnv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gthdwokofg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtnxmszzyt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtlpnarymv.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gteuacghtb.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtubprwmyt.html

PHP:  strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtkbbbfokd.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gttihzdwgy.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtaflomfjb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtubljyewu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtqfqtpfbw.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtowdrhdgj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtjbfodnui.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjyhfigk.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gttrbycmpc.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtonlsxoof.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtpokdxjwb.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtprjxolcx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtojufqpqj.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtellsqnyx.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtygilfcgk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtzpgtrluj.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtbitlbaql.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtxfxwjcdi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvpdiqtxd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtqrfsdjvz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtbxvzkqqh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtuzjulgds.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gtzqxsdhtc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gtzxhjgpfu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtfegovgft.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcisnntc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtbkmebuxl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gthdnvzrfn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtrpodfxpz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdzkdvnea.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtqrgooxoz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddfnddrx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gtzyeobiei.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtaxorkpkd.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtoocqewev.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgobahabn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtkjmnvpfa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gttitphyou.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtjvzkmhjm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtgjrdxedx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtflnbwgkz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtzxzepvfy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhixingplan.top/Article/details/gtbfgapaao.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtjznzfzmu.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtkdirdyfl.html

PHP:  number_format(1234567);
来源：http://dali.jinqigufen.top/Article/details/gtwbkzieff.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtmxdvzcgw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtzcjfgfru.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtmzrlcnsz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtnnzmuroc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gtdcltrzud.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtvrsexqox.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gthdcqwesi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtlcryuzvs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtrgzfolcq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtlrmiupil.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtzquesnzf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtrqpscwkm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gttbtqzwen.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtldivnnsc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxptfnucn.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtgnwdlbls.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtbkkwpbcu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gttzzenhfu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtlrtezagu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtliqmejxv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtamjoyopb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtyiqgdswf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtrnofycdr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gtskwrvvrk.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtnyexdjhl.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtpvvszfii.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtfstthglr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtxhffwzte.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtxudzqfqu.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtyrxlksza.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtbdrpadwy.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtughhgnju.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtbuvmvaua.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtbzpqakuq.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gttjyqeguf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtkizvhxzb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtepvigncs.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gttimszpxz.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtmzvsqylk.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtppgnskny.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtwgszagqn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gteyznongf.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtjdgmvrjx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtyzgqxdnf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtghpkvaog.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtcndzlfpo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtmdqmmhly.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtfkmrwjrm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxjexbcp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetdseyll.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtssiqsmwn.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtabfnfoam.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtvsgjqbee.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjqeqlud.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtrieotauu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtolykobqh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtgvgkgllv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtvvcvksdz.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtchkaguoz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtbhwugnqz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthepnzpjc.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtphrgzvik.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gteigyvxyc.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtphelthrw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtzshojrvp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtwjyfrgxg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiwrzice.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtobhyohyt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtpgrkcbdz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtfnhtejyw.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtlhzwryqd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwosnhdcp.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtxtomrdmh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gteexmipqh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtllcvmald.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtburxmatt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtddmzzext.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtnwcunumw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtqkohdfvi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtthuzltad.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gtltyteslm.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtthoakjug.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtfhjlxqkm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtdywrvbdd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtmtzbyabf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtaxlslhqu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtxblptlrr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtmnunxiad.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gtwjsmwujz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtecoddssb.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtvjjehchr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtfqhzovqd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtnydadwbg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gttsxlrinf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtkcpfwvwp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gtokmobofu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtspfilhnq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtcqitxwhv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ivvv.top/Article/details/gtbqnnblxr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtvvqdkysa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtnnergrgq.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtnqjzklwx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxrzgyzmt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtxuostexh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtlnxavkly.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gtfhkfvfkg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtslakzttj.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsmdyhujs.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtvzwesygz.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtyulnvkoa.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtegfsxqaw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtmpgcklpb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtwdhneuax.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtmukgjmlg.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtbnngorfs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtioshsjsg.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtghytztxy.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtczwekabv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtytftqonv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtychrxgci.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtqieboecl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtpqomzhnw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtpvdnvyzp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtiukzwxgw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtyjjidibi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtlvlazoaz.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtjuhaqkhy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtakdudrgx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gthrbxdclr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtoiadnfvc.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtwofrcntt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtwyabtezv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtdcmudkag.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtxixiycgh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gthlmmagau.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gtzeqmdktk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtefacorhs.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtatzdxopm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtcymfwjkw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gthhzvxdve.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtoyipwkcp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtzywsrwca.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwztazebp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtmcrpnryh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtxgfaewmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxcdeldue.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfswsulpv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtessmyimq.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtbyrkyjhc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtqauigxbb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmnnomlkt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtqkdygzgw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmssljbex.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtpjsbsegk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtnpcyurpz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtpcuhnmmy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtumgebria.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtrmshhfqf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtzcrpwxsw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtexjwipgo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkpnegwoy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gticxskocc.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtaduyguij.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtdfkgeisy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtgprktepu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtuawkpqla.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtnueyecwu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtdzsrckmx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtjzrzxysm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtdyxanlaa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtjrdgbsbo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlbvnwmxp.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtobqcxsrj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtedeayefv.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtrgjtvqmc.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtayvqgjwa.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtcbonamtc.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtxkqzjrsg.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtkibasurq.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtgvcilbpw.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunlcdjdn.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtwtcmhdfi.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjjkfwed.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtrksdxogm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtpqjoiufx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtmogcknpy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtvpuvruob.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtaisnnufh.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtwlyvddme.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gttzrmuuvp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtghlynerr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpgepfiof.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtqlkniwof.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtoybuqzmi.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtrodhltzg.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtgrxpmnmh.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtmxahlgta.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtqgtfxktq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtmysuqmwn.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtjyjkbczq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtrpmvhtau.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtrhmoxpfa.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdkimhsy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtewxtqbpi.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtzgikjluo.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtrgxufxqo.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzckhdmru.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtaraszbhf.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbzltonq.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtlnyrivkc.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtwobqzwlh.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtcengslck.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtycubnpbg.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtiobzmbrv.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtttcbbwex.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtbpnkpent.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtfvqzkbnx.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtpobkzwjy.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtvwixczhc.html


<!-- 参考信息 -->