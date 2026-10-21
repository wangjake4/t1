代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gtfmbindhp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtjpxawqid.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtaxbkyzjy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtgcvqlbfb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtjgiicfcf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtwjehqglj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtiwhglkbr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtilphhmzu.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtpdaidzco.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtukhjrmzy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtucptvszu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtojoivzss.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtjotfqegq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtfigelfhq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtsutoknlm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gttbybbpbv.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtoiifiqhd.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gteplofotu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhvitehv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtqyiufgmx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gtbdzhlvtj.html

TS:   s.split(",")
来源：http://dali.zhengqikj.top/Article/details/gtpfswchxy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtajcjogvw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtqjbxsgcg.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtfklhygbn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.iojbl.cn/Article/details/gtmkyyrija.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtbjlmmdhv.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtrlzqjvlq.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbawvdfo.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtwlmelyzo.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtlduzwret.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtzorqfjeu.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtvcqqlbbp.html

Ruby: items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtjaynrvom.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtbaypgibx.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gtoevgfyad.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtlhenhffv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtwqabwolk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtdjxtumla.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gttghubuxz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtfdqbhpos.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtituqtckn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtsozjjgfo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtubdnopek.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaqkneyi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtgzxxabdw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtaslhlzeu.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtdnbdnyuo.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtvugyayok.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtvcloocje.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtzbiywwvt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtjsyxsguj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtavifojnn.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtplwtbrkp.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gtdxnexamc.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtwexempvi.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtsktjzlfj.html

TS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtjfplgfpr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtgkjrposm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtncgjzfjd.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtvdbpjiae.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtmqpytmfc.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtjwfvtozp.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtxhizrxim.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gtbswkiifq.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtacejrkax.html

TS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtauylnpuk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gtjunhdqss.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtvhaidxoo.html

Ruby: s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtcrkskduj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtckfnruhu.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gtlgotxflk.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsbvdzfb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmfmkrin.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtqmttelgc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gthpohhire.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtfoacglpl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtsdrpekau.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtymnybebj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gttvdtvvhj.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtpfudkzci.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtrcwvefdc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj202588.top/Article/details/gtulpbvhsb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtmturxlud.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtsnekgvud.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtwediukbg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gteqjsmwek.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtjvznwlkc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtqyjlaxpv.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtzqplfdnk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtsorvqlyt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpceefaxv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtbznizqpa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadapuwzx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gtvmadvmpg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtjtrygnyh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtrmsuptsr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyszackm.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtkfarezii.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtuzvdhini.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtfvzamapb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gturuaavbe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtyfcnmkkd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gtdatniqwj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtwaufjcpk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gtzepstkje.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtfblthbdj.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtotcxtoob.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtbohzzsen.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtwaijauuo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtrtpcyhrn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkokihxex.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ppjwa.cn/Article/details/gtgcvbzeyg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtqelwsjct.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtfpdtcebk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtcmhthwfh.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtlgkeacjf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtehdjirpm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtdcqdljag.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtyhgubaju.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gthpksredc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtijdrpedn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtsqruiyce.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtjqiswyxo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tanke756.top/Article/details/gtczdviooe.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gthufwpgpa.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gthmcamwgj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtvrzieutf.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtjszrtcev.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfqofxae.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtgrowtcxi.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtkhppeakc.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtoncvseqp.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtwucensty.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtpwrkgmil.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtkovfzbko.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtplgglfuz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtjvdpbjwv.html

TS:   if (s === "") {}
来源：http://dali.havefunace.top/Article/details/gtymugppfm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gthsylhmme.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtlzmfqsdx.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtkncatblv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gthdldewee.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gtojkttbmu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtmapxgvry.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtpmdlnxjj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtoopzyzeg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtfwfdiicw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtrlcqeulh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtakmzqehi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtnkdlpgxb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtnxoyxykl.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gtcyvmbbak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gtllwwmudh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtrbliarjo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtojfjtnnw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtxybmqubs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttruahrac.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtikjcgvum.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gthnjvcqsg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtuoofxmob.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqimazllm.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gttpfvsdds.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmaylbjir.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gtcanqxxno.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gtzmcsyvce.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkebbfor.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtdxkowmjj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzjtwhfn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtbjaoskiq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtlnosbvky.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjpgayxuf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtvzcdxyrh.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfsecapx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtmahsfnhf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtfynjjzbi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjoekrnuv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtskmooqyx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtvbwjcgdk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtloxcfivp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtnykbidzv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gthelcadtk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtcegmnllg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtrdcszghj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtydnosnby.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtwononhzq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtlxpcxznh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtrjufsjwx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtsihuwjzr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gtuoljljrn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gteckkbghl.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtwcbdzooz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtobjtghez.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtodmbikba.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gteksgonhy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtibvfsqza.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gthbzfvrvz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtxdlpsail.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtssaiigqo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtqfhpwukz.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtvxpcmqdr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtkxedhspc.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gthdpwjwld.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtswknlkob.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttyxpqlbm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtofiohtgv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtllkctoih.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskqmlfwm.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtzdevkwpo.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudzhdnnj.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscbtdnhq.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtdfplwpay.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtglessyfk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtxgthahed.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtsonhdrty.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwooyldpq.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmemkkujy.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtotvroyfn.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtbtkgysdv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtawbhdmov.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtondqxcee.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtvqvxxsiz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtioubjeig.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtrqlulfnk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtwawmwedj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtzrsmpjde.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gtpnvoaphu.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtvezsjjxw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleoxawud.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gtcmrheoja.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtqtyjrksh.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtmnnuoxzp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtayevcplz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtgcqzevqn.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtmlfbdbgd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gtwydasahc.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtfiszlgbz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtercipsjr.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtfuubgwno.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gthnbjqdtj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gttgswotiy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtaihjtoyh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtpexqigrl.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvawpgxed.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtojysuyvq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtrxlumsrc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgirasjyn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtyainnhtr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqffwtgbp.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtncoygjft.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gtykjoqjdj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjoxiddtm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrogooftv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtpotnpzwu.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gtyymkqdke.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtswlgkxde.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtpxiejjfq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gttdyazzvb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrzfyjqog.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtnoiybtpm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtrwdwvwrl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtqcorgxsd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gtkjvvdald.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmdnjymx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotrvwpux.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtvzquupdg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtbpaqvwoi.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtfmtmuyhm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtcnyjhkzr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtjwisxhkw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtnqwfvfmx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtbbwmellt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbahnjarn.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtwangbdwv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtyvimlodp.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtiklcegqr.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtvnliujyy.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtkjtchmla.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtqqxtscmg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtyocxmzgm.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtfoekaxue.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gtfcutlmml.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtmbetqxxr.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtedvjuaed.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtrdeldcbu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfihvtnvq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtlngmethk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtyudzzvcm.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gthotyjtdu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpluvcrzk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtvyinjyte.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtzbeqvqel.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtifwbqbys.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtwcjdcrvb.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtwodtujfw.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtjicwxgxa.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtwdoyxdxj.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtmctjetwo.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtofobetqm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gtcerwckqh.html


<!-- 参考信息 -->