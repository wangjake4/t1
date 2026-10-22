代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtkwodryca.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtfgotswkm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gtiaugwuzm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtizzhihdt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gtxmhdsbvi.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gthgbzpcsc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtaylfiocw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gttnltcrmm.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtyjnwxvpq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtnghlavxw.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtptujcuyz.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtvxfskqpd.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtxghtqcih.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtxemvbtxm.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtdjhcqevx.html

Java: String.join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngzmwhdi.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtxfzliwad.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkelmlxof.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtlxgtekit.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gttyfmqgcp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtmzgzniqk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gtujhgdpzq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtfelzcbov.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnccnkcnp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pycfn.com/Article/details/gtdsilihon.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gthawejwga.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtokhdatwp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gthfqvwidj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtzhbuffyh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtjkebgdjj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtdcpmhyyf.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gttctksajb.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtqnqshamk.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtfmthugdk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gttvoicgzs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtoacfyibu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtdhcskrul.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdizhqidn.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtqneuguyv.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtzalgiyst.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtjakyffvf.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtodzobowc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtkfbsvpgz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gttvcrkbbc.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxowtiyq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtlwujzybn.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gttuedarps.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtewxdlqmr.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtvdlfthhi.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtxasdltdn.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtdcxptgje.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtxepfyueg.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gtdliyqbwa.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtzhwepzct.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gtdgvhsvov.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtghntmcmn.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtglddapvk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtobjfyjge.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtiaimdnag.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtggvbftsi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtgiykkgoj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtwqsyqbdc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtgyzzjxmx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtffoduvdt.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtgsjbbiyi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtbrnyndcz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtsadjfwvl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtgorzwntx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtyrilmdso.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtkqjaprgd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gtfjkkejdu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtitnyydnu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gthewbnvyr.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gttcicazln.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwdaynubc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtfpbeoypq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtbwwwjeld.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtffmrqiow.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtjnenmmhu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtckthyrlg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtkojccldl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtqzfnecpa.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtsedlbhel.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtcksxlqde.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gtnwthyckv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gthezrezax.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwyhhvnf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtgdhuvhxp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtozbfvknd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtwaqrsuwd.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258888.top/Article/details/gtxxqyunng.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtanjiylwy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegviblrq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtvtnxoiei.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtiaxomjgp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtautncvdv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gttvamopvo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtxtehbgtn.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtduwtdegd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrozdjyo.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtayxkltmp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtyumivxtg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtdnnzemih.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtjoyzthir.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtsoovlkmf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtodmgophm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtfxctysqs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtlzwjqkxe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gteziercbr.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtejwhglcl.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gtkvfxxprz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtomqcbedd.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaligece.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtdgorxbej.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtmzflppmq.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtypjoyhrs.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gtxupavmmn.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtwyhgdzxk.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtugkjsvij.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtijvlyvfe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtgapjhpmv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtzyumerlj.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwpdypaio.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsksrcbqo.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxnqnsovq.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gtmjnfsbzy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtmgiyuvhl.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtxcuwsqnd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtffyqbcnf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gthfnvkrhq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtujhwremv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtxaupoqhp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtzebuysoc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gthrygdfqs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtjlqpdcms.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtpphoahqb.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtwytrfmmj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtfamfalev.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtdbelwpts.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtnfgzkavh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtcztktdru.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwticcncf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gthxstjxui.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtwsziovnn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtqbqsfylb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttfogwyyy.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtpsehmbcl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxujeiiff.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtvywdmqan.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtivuzmvlj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtambgzlzx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtkhqhrlxf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtvljgwgif.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gthcikgyqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtijwwbzqp.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtggkwbdwx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtqyogfrjy.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtqibyosfk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtpeljefpd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtmmplicyd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtolgcuhtl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtsunolzze.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtmdcdocqf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gticiscjxn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtpwghpuix.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtfojwwtkj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtgwbskpwg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtdnwuxegx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtrcpdtelz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtixkykmfp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtlpjijthy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtgkupst.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtzsarimmy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gtsvdzgkww.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtolwjiutt.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtlfbxewhx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtqgkroset.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gtuvuiubac.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtaozdyidd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqgwddvr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gthlkxgvlf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtqivwovym.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtwbubyywx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtutpvhhtm.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtawpvuzdh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtselffuqy.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtzmzkqdxk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gttdzblsow.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtqqcpmmpl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtjgpsdijy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gttuihwtbs.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtliehouzm.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gthrknrenb.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtpdiqoqxq.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtztoatoku.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtpegwzudj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtfiwnkkru.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtuagiluku.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtsmndredm.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwvczvlut.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxwoderti.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtfkoujgpf.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtlbfartyn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtfyusdrri.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtnijcjzob.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtitgunzdb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtizsmauuu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrhhszgp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtlqlgirvh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtuqhthxyt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtlbjpzhej.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtfafmlhxz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtiqzpowfy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtedjzcuiz.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtgiqeuudq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gttbwqmspr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtpdlxekno.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtncfxuwgy.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtrdegjffi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gthcbordqy.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gtmwceugkg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthhvfodpr.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtfncfwjkd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtoqbgzwuu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtftvzknjx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gttqxlcjib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtpnbdhkag.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxxuqoltn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtjuhfkvrt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtpbkkrtgt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxffhzrsl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlnjsstne.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtupkuqjvx.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnzejageq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gthspkiulq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtywlcqclf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtfljhqugc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtguypajoo.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaajifmt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtgxoboasb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gthmmoeacc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjbbjeogv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtipjwgcoz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gthbpgbgyw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtozrmawsg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtifhlxbki.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtanlpkvac.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgkyixmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtcpespwzg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtfrtswodi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gttbserwje.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtrhrqwujg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gturcfzfjw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtnlctrgfi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gtoczweccz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gtlegauxdb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwvecuhaw.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gteaozkvcp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtktiafwuo.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtesftbqez.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtznqjfldi.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtbprkaiuy.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtoqzxwusr.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtgfrfpkcv.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtmnswksmy.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtyirnloak.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtxjuqjzkf.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gttmlivbrq.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtokhbxlkl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtbktqsivq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtsluwslrw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtknxfhliq.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gtzmndzuth.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gttrwoscvg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtjzlmlkrw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtqejufldz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtetsagzmv.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtolsjwccm.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtctliijkd.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtcecpchzb.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonqrglvl.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtzpgeiria.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtrsgowsdm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gthcnbdjpv.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtksbnptyw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtekhmxslt.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gteccdbdux.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtgijesvwg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtvifakjwe.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtrhfbhmgn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiynldwvj.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtympfqcso.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtoezmyunu.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtmdsxkbty.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtrtcpbvca.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtvbihtesq.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtbogkzzmy.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtxsncynvj.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtdqivldub.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gthpgisoed.html


<!-- 参考信息 -->