代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtewxidzeo.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtmeyoliey.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtyaomcsyb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtkuhrgazr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtgdiemxtu.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gtmuuorefx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtkscaafwp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtazpwrqax.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtdwefvzdh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtrfdyptyq.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtnptgacni.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtumddntum.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtlbujxgmj.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gthqweaahj.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtycujmyxf.html

Java: String.join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gtzykctzqh.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtfvvkurre.html

Ruby: items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtbbvyatmb.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gttedccqhh.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspuboujp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtsjldjbyo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtelwayfpj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgachaba.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtseihvgnt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtiqdwshjm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtrplhgfgz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtdhjclllm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjclaact.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtixhbjrcs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtqfjerdmz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtjcrjzhrn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtmczamgys.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtyvzpismp.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtfcsxuuhv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtdvqemcom.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtdghnpkab.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtakcdotff.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtjqdfinry.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtebdsruzv.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtlvcoxmku.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtvhobesyn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtkvinojqa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtqpqnvmll.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gtuaowulzi.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtzizcalms.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtjwycdxow.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimoravlg.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gttpeooyxo.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtmbsfpvfv.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtchyitvso.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrpndbzh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtczqyebsr.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtlyjfcioq.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtpveobcek.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtuvpzrlcg.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtrtnrauho.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gteesviial.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgqjaemnz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtfczybkas.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtgncksldt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtrephjqhp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtyhpfubdh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtxrwhxkwh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtmeypzivu.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtxwuxbzsb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyxesgnr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtiboxnxva.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtrypfheac.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtiwwwoctu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtrenjuvlr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtayidxfha.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shzxlz.cn/Article/details/gtdudocmcv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtsgqburoz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtcbrzsisw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbnghpnrr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gteffwsppw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtqbrttphp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtmiuestuc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtiluiyojn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtnnkbmdns.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtxshwmczd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gthdsostjy.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqjagaaq.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtqpchrmsa.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtgoqqinwi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtdxqtyjvp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtdwxwldgc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gttqlfymnf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtjbyfaaue.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtwhbxbvut.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtitaeonux.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtsfyeniet.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.mhx1999.top/Article/details/gtpupwxsxg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gtswlscmgw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtxzasgfxg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtvfktxb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtareaxkjj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtfcriosit.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtlfbbpctt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtwvviyyho.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtevfcycic.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtoccxmkmz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtquwsukjt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtpsqetebj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtcoyalcqv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtowukfcfd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtapcouitk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtyaznubtw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtbbqtjmsf.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtrjneadxd.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gtbuvkkjng.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtfoxugiyg.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtknnijrzy.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtzwsyjclq.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtlgonojpm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtquochloy.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gtvsdqsoxa.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gtqruhchxu.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gtocelmysw.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtbfurcpov.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtkesfolvl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtlpnuvrjx.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpddsbjqv.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtnwysoigl.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtxtnrbmeg.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtuxdvawre.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gttzvhfsib.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gteopdcrhi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtiqhjybgw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gttoalsxkp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtzfxtiksm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxwiibdr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtrhjhlaja.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqwvonos.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtppxlgxns.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtejmpjrko.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtugjuvdwr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.svipenyu.cn/Article/details/gtsmqvyaxw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtzksalanl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtthooycnx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtahfodugc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtcmnyhhke.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtztvvyslb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtfbkqtzos.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gthhsjboas.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqsgooxvv.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gtvzvfccua.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkwgucnga.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtykhnpyjk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtuhfymcls.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtzxxuumsz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gthnvzwlgd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtnfxqervh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtlqrgvyro.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gtppztxzoe.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjczkmhns.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtnhrnhuvq.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptxxuifz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtvwcitvqu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtqstaleam.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtssedzfvd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtkoecefyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtetpufqdt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtsrtrtney.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gthziijwby.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtooulyyxb.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gttukufqiw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtgtwzczzf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtspjvdcds.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtyyzijmkw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gteufxilox.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtiqzgxwcq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtytihjrpo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtkjqfqkmr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtheshmuuh.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtlxzipzox.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtboicawga.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtcicmvvwr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtnhefjuqc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpyhxqoo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqmcbaet.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtfwypblqi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjwmvzyx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtfhshgzom.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtwuvbpztp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtlpxglhnk.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtpxjjtomx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjnkefpmz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtuiltzvin.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtzfkqwlaj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtwkufttgd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtivddatup.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtrutvfvfe.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtzzrjfggv.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzdpsafeh.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdjycyvs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtkijhbpxo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtskrtkitl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtbngpofvh.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtffmaoavg.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtetjoktbh.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupxczimy.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtvmggyefx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtzeqatyre.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtpirveexi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtobqvozir.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtzqjxfwgv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtnnfxtxgp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gtwoelxxvx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtpknlyqnu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtyyfqjglt.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtyzxuifad.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtuimrmqyy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtdewrslxa.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtetscpxic.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtdtlegckp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtljdvtpij.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtzvshfqla.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtunokyqev.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gttagcqxgv.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtyjvxkdzy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzzzixtru.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfrhowdt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtrzgilbju.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtmdjohejt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtoshhepvw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtkncferrv.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiirisgx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtxlvsqnmw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtnoeufwsk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdalgxcxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbkqqgpvb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtnlptxybo.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtoyhkzsvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtcbrkngrf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtfamxpizh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdfcxdlis.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsirgbkyd.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqvyjchxy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqhhbgmir.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtmvdqvubx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtscdtyjjk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtketrhpvs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtflaxqlim.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtidmxdkrw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdrebnaiw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtyctddouw.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtcojuvkkk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtpxjobedd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtufsqtoya.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtbroxkbnk.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gtvtietrxh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gteizgffte.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtwfxephwj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtgdjwlkil.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtzcrfghre.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtitikrwau.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtxfnbudlz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobetioop.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtnrcpgnkz.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdipapcy.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtmfqmuzft.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gtqkowhsfo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtizfnouhu.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gttyzpkavw.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtyxyxnyqv.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gttfkaavzo.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtuxvtgbch.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtoecaryzh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtgkylwzvs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiivstxf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtcfczncwr.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtebqcvzek.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtbzjtouli.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtmmobteup.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gtagqaldqw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtwopmgvpx.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gttwpgwmcc.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtbidyzfis.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtzzxsrshy.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtuohrchrw.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtxwuivfne.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtjnebsoea.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtoemppnkr.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtlvywtxju.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtlrxhvgsf.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtwdpfhbqv.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtdmgcsrwd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiasuqxe.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtcfqiiegi.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gthjyzyaow.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtbagpljqr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtamuggadl.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtjymxenxc.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtoiabcfek.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtcrqmmjoo.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtkggqqree.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtgvbsbjzd.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzpmsgfdh.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtadzegxwj.html


<!-- 参考信息 -->