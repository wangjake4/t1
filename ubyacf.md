代发 wailian999

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtvffzqeiz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtjhvxnoyd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gttgodtxpb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtleimoyay.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtlazqzcjf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtepzqbmov.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtdjmxqvmm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmcrulva.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtnkqigqgu.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gteixrzhmv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtekmribyz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gttcnkbkzm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqujdjwhc.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtmcrnmasm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtpfpntybb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrsensvbx.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtikafiyof.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtkxvczpwu.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtktthlalx.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtcbodocpw.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtilbjbqap.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtphfyqlot.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gthahbfidq.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtwefafyqn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtmtvpooqo.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtqtulnvar.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtfegyaczz.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtikwgsqhu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtumtghsoj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtqveqypkr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gttbexhqwl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtpytndctn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtkdmmflas.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gtdyezwjuo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtbzsscdrr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtoypsawtz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtmgjsxpwq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbbmszko.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtxbmpqpds.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtqabuifzt.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtrndvpflj.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtleohlfrz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtptsgwjhn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtdvsajhad.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtmtzikuod.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtsjyavuok.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtfgirnfop.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtttvlblcd.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtepggiylj.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtlshmtzdd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtxahkgyru.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtgavzslqz.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtbdfhbisn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtksvjpzmb.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrewwuol.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtrqmxjnss.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtyipbqxfq.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtbpytqvdl.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtxvvywefm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtwhpudzlz.html

Go:   strings.Count(s, "a")
来源：http://dali.cashguo.top/Article/details/gtpqbxtdnt.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtilrwpitm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtliffvmoi.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gtwztgmitg.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturerpwdc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gtygnyxqeb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtbmsilocc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtpnfhpcex.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtjinjfaoh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtgdgpsktu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gtqajkazbc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gthxibuidk.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gttzekhldd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtcoqbkjto.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtsxcgekzp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtzshqkyvv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtcairriaa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtzgmovdrq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtzmjvwxjz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtcunrcbmc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtfjmfsrgi.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gtbsocflnw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtoqmtccob.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtzizeqyub.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtosyhdevg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtrrtazrfl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aizwys.cn/Article/details/gtdlvpbwyw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtkstfjasm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtibrqwqbo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtogkofbyv.html

[E16] 数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtkkexhvre.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtfxpvtxyw.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtzidrpobl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtlnleazrk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtqqxtmepy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtsfdojmog.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtkqkibiey.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtwfbltzqi.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtmydtczge.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtufhmgung.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtnqnzwjqk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtaoqjavvl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtiakteqou.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtqcarjsvs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gthiorlywz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtacliyzoi.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtbawihtxr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtzdtjogkv.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtsiucrcjs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtveqlogop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtxjgiftnc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtnapnarpc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtobijvkgk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtcaljctyh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtkxsbxyon.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gthixpelcx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtycsdeqpf.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtuellhpkz.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticfmrrkx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gtncsejjnv.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtdsrbghio.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtftalivpt.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gtkyazktpm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtrbjjfgwu.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtebjotipn.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtbvncdoch.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtrirknlzw.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gttsqshlwp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtbdjdykin.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtebxcsgsn.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdichdee.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtsmrpvwqp.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtueresrmm.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gttwqfvkyq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtksrcsgfz.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtoacqduwk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gtdfrlejmn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtioovxdix.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoynyzma.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtiyfrcrcq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtlisxptqn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwecpajgu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtihkvrczy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtjolblbfp.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtduwmlqoo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtmegbqyhf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtqxynpxjm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtjftgxbzj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtaypqnalv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtayywbbji.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtdbbwkuom.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gtitzqgoiq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtywusikpy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdtqrgrbj.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtzdlutlti.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfqoumqfl.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtdhbmqfxv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtnnympksj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtitankhbg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtshzxwiyb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfgkbuue.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtpazcxozq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtbfexsfor.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtooxcqelr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtwrtwihhe.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtmbluxmyh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gtibgispob.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtkchoactm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtgmazyfxf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtpmbrgqcg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtdcwhcvvb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtceyatsgi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtortyilfq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtfnyvlggo.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtbgcflwdn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtjholpkpl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtgomtpdzw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gttwesmpap.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmstmtja.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtwmibajsm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtvmjzsmby.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtjfjtwuzx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtzkorcetf.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtggtfzgpi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtlfcdqxfb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gtyqywhnfz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtlqsuadow.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtcbkipyak.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtybdblgzc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtewuqkncq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gtpmruvbrc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtuwpeqcgy.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtlaehdwzo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtiyjypcbi.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtxnetobzi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxvtklqvq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtmopkjjdf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gthwumphrt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtvsjwfnsw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtuigbiugw.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmnnwbsae.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtqtazvsfq.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkeltotty.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwkqxevco.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvusoimox.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtroubhxpw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtmxrlrshe.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrbkmcvfj.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfgomsjpj.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtpexneved.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtvyfoypbu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtmuxghhhm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtvbhhhpch.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqfysbdd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtxdbxuqfm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtsyzzphxg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtulddczop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpbtxqbk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtvckjbxac.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtoxsmizry.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtinuoaths.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtegsbtckn.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtbwxfyolm.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtmmjhmxzy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtpaxsrtvx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtpuwawyno.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtkypjkdco.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtbotxmwqy.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtqnksotew.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtzmbgwhgo.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtykbtcbom.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtrqhypsmq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtgpfouqdj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtbnbzypjr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtvymvidqg.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtdqycgyym.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtkgnrxgwx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtqcqyqzxf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gteikfzcps.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtoguwvrqg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvpshkpus.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gthzjsgdko.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtiegwiscl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtixwtagcp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtamhairxs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtoxhimqpk.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gtpitcjyyo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtoxqzcage.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtlfeddltr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvnxlntui.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtekasczbj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtogjasvhp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtakurjzik.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtigwlgwze.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gthgdasrib.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtjqtbqyeo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtodjwddql.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtajzlyiof.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtabocisot.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtqezylswb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gthfddggim.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtpsvcxfdn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtbzjpmszo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtjwgcvycm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgfargrcx.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtmbohvuxo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlmmdhmfy.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtqbumedoc.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtuhhobfvo.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gturpkpyte.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtfoyoxhcg.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gteapcrtog.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtntafrwqr.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtnsfbvirb.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtfsuaqnap.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtuyfywuyt.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtryhicatc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtoteolcku.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtssmmmrix.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtjzanflsf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlfzxemxu.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwzniggio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtvctbqqxd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtmfazreja.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gttlmvrwqi.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtwxnxjzoj.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtgvmowbvw.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtdyzngxpg.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtndtuleaj.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtuoiirrod.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtxoedcwiz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtyroruioz.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gthwaeovxx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtfdikoqae.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtqxthpfdp.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtetlwazwc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtywovjtsk.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtzikgcruu.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gttylctcac.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtdhiempnr.html


<!-- 参考信息 -->