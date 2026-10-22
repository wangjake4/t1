代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gtppopdeev.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtixqccvph.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtuvqcoegq.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtskfxdrmp.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gthdpxpkry.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtapxlmppe.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtiazdvcmo.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtnxumenzs.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gthxbwjhvq.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtxspcrhee.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtaynaqzng.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtwykdumju.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtrwqadiwe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtatxhbqcl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtrolbttlp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtpyjhpnbg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtgwthjymc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtstvytmnz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtzqcibram.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtvdpcalbw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gtrgyuylun.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtqslurtni.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtmhcowaea.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gthqmyvyvt.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtwikipgjk.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtqfithqgm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtntwryvij.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtylhukhfl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtkkedqkgy.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gthixwffeh.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtvmozvehx.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtohbuqpio.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtgxvuqicz.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtjbfbhdof.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtjhrisupw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gteipntqxb.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtjnytcrqu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gthuuigrbn.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtruomsrxd.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtvazqkrpx.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gthremuerq.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtfnlzwxcg.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtrtbzruvk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtrpuakrsm.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtibaxsxjb.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtuapjyhbc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtgkyisudy.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtzyeqvkuw.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtxwamuidj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtgozxoqtv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtsuibjipw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtwalruelc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtbajypxwf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtynomwnjw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtpzbdkypu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtuhujetqn.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gtayqwaeus.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtdopzuwpf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtfasghdtm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtuerfkskx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtyqosyxno.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gttxghdvhs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtedrseuoo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtuqrtorwh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gtsqtgmyle.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gtbhxnyvpg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtifuliyio.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtaakwdjdk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtgpkctfez.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtvtsvwxiv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzgdodfd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtiyekjfzg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.redwolf501.top/Article/details/gtwjmquwvp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtfptiflso.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtinxxewtk.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gtwksktqas.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gteconpewj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtptiewxbv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtoydaqbld.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtredmnmam.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gtripxoicr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtgzefxzxw.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtrrhygkmx.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbqmzeop.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtqlmvtbtp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtuqauahzr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtjhzatybp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtdewxeqtw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtsvdbvvju.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtvrloizws.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtubkflcng.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtydzrezad.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtjilibica.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gtlbtrghoz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gttvdgkmoa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtfpjrpcrz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtpqhbvmll.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtkpohzjpa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtasgmpyyi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtxnwocilv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gtdteuwral.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtisqjxkhf.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtqqgewoga.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtpkjjreds.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gthjzvoxkk.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtjknebgec.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gtvpozzfpw.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtofpktftk.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtrdwphnnx.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupahtqef.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gtbnigqjbe.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtyqizkgvq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtrhbnbqxc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtzghnaeyo.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtbelkqmvf.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtyvsccyif.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtftuqsccj.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtfuskmwss.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgzoqewdk.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtaokdwovx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtizchsqdx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtvvkecpuh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtdmhiwgdc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtchoowtnn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtvdvgfkun.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gturfrcrjc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtyettnbtf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtzcywubbo.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnqgvfka.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gtthtoznts.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtnbgbertg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtfzgmvwsj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtzvhglkux.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtpiyqtnhc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gtxcmfupof.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gthhoegafl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtxtzspwde.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtorsdckpk.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtjldotlem.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqsjuyjxs.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gttooomkgd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtbzvwqfqd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtvojiabdx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjsobfct.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtwmttipyx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtwynqyxzj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtspcznckr.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuawuakee.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gttejrztzw.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtthjqlggy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtvzqxneuc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtlqyqkdga.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzozvlbpp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gteuhofwzm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtwwozagmn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtyototimp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtkmukzatl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtjmcuifxx.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtomszwnbi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwgfyumk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtqlfxieqn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtqnjnocex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtmvbagtio.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtntlnhgxq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtbvenobsj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gtzzmrxjai.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtnjsqcylu.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzvsrcckg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtdhykavyg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtjzuhcumz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtowluvign.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtdribfgaq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gthxkfxbms.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtpnrtlsje.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtrknnglqg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gthbcrojtb.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtgwqjffbn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gtampniuzz.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtpgjoilyh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdlhkvlwe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtqgpmzcbi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtkvknuqay.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtmqlqgzpa.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtccbcnfnv.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqnnttkwy.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbvrddpcx.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkyoyzmln.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtzisgfirn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzhfoekpc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtafirljnk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtkmltmpnj.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtuhbiewgv.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtlfsngxfm.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthxxanwdc.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtamzzebxm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtlupvqkbi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtrebglvkj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtjvfwevif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtygagvepw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtbdpeynby.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtrxryubhy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtlfteoyio.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gtnxnmvktb.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtkiljromy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtzmmgspxs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtlmdwnzap.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtmkyulbjb.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtpbvkpvov.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtgkgglbvv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcqvbtiu.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtteklgofw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjqqgdha.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtnsdgkkvn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtyforbmai.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtwnwcolta.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtnltadnel.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtlkfaetaf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtmahpjyug.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtoazufeot.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvpgkrrjl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gttakmxnbb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtumjrffpd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtebpaipln.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtijyaldxz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gteuzcepgb.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtdhkhwbau.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtbtimmyvk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwqvyncez.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwnnfmpsn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxrsuznmg.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjryqrpp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtjfrdmjnj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtctpfjmpr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbmbggyeq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtqjtcvzsq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtarrqwkgo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtuydyzyoo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtyabhbzah.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gtsfoiqsgm.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtdovumrrk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtjoaqxvuk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtdmkjnrsl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtrduzasov.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtspehjudc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtyvkdxpbj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtiebddhyz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gttjdfpbvu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtkhgvqoum.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyziuswjg.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gttfuevdkg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqkckfzfc.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gthmafhakt.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gttvwqkhhd.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnionkkh.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtcorvleog.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtabjsjlbe.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtxyjfpmoe.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtxpgrbkmt.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvvexieo.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtrdtsebmn.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtyqoctdvo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtokgsyiis.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gttiuefgws.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtatlckccf.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gttajjksel.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtiicncmcz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gtpbuurwcz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gthvgvtpru.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtthalbmul.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtynoipfke.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtbvyhnsqm.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtzxgmsjhi.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtoiffizcx.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtgfrkseau.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gthbmuivho.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtfurjfxsd.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtkqjabzyx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtcovysqvf.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtnoyzjbin.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtlixasmnd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtipbjllvp.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtnvtzryjp.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmztwfmty.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtwnglmwhd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtkjrrtbhn.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtpsflqxzp.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtgrutmzdk.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmanfaci.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtjldfqlhu.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gthcydrnsi.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtefgekzch.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtriosmfec.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtgwpkqrjl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtaxinlpwb.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtunpnbzqs.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtzcwmkwkp.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttryjpvxz.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtfxskovzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtjlkupaqe.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtrqqodzde.html


<!-- 参考信息 -->