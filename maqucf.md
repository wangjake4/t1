代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gttjvqhflw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtcuktjffg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtofynmzod.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtihfljnkz.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtzeqohmdu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtkvqrrxjd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvqybjmk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtgghjxmso.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsslebyxs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtkwehnrzx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtsyrvtwmg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtuembavpj.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtkpvygfro.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbzuusdd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtslhemfli.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtcspfxpfs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gttuzysfcz.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gttswiavll.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtspkedkpj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtufkdpmvr.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtgmjvcwmd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigufen.top/Article/details/gtlxhtpnds.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtoeilswpd.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtytwcxwwp.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtqqmrxytv.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtlzlfftsu.html

TS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtzvcsgxwq.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtwihrvtyj.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtqrsiufgm.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtjfjrcbcv.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtuurprrpy.html

[E09] 去除所有空白字符
来源：http://dali.chenlongwang.top/Article/details/gtymcyxzfa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtxmhwwqux.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtqbpsazwg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtzjbhyuza.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtauhovlvo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtyvpuslrr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtvygqxloo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonpsrhmd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtwvttpnpl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtryfoszxn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtvenfeocx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gtqixxfwmg.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtagihnzes.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtgixpugxf.html

Java: String.format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtccmzkktc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtbobhttwn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtmzpkqrzb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gtubzrwpxw.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtxxhjbhcm.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtulypffls.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtcjexrggt.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtwuhlodfg.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtbxleoyny.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gtvxgvsixw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtleexaiee.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gthmmlwudk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtotjwjddj.html

[E12] 统计某字符出现次数
来源：http://dali.redwolf501.top/Article/details/gtvtlhimvp.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtfgkobruz.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtijogwjbs.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtkoutlgri.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtuwquqvgy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gttgjixwcp.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtpgdwxgfu.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtzmritjeb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gtzwrjgyul.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtgclqfwwm.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gtgzfhwmqe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtsnwoppwl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gttuxwkzoc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtiniqgefg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gthfuyvgse.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtkdczmdxq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gthxxbpaid.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtaqumkrqs.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gtzpjpzqgr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gtwxhbygmc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gtjcqvmfkn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtslwqdhvg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gthgyefues.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gtgxqcbheu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtfxqhowfs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtvbecwlkl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtjdvukrwv.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtwilbtzvp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gttbslshak.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbzkfeioj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtszkvtjnj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gtuguwbnrf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtkassbwlq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtnobkgqzr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtuocualhb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtxeybzgvm.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtjwicuejx.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtlgrgtlbq.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtecjftrys.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtghvndwqh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtdsyzwzdr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtxvenecww.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gthhmmhdug.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtnuswbxub.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtuplhejzm.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtxbpnoagp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtcltaetne.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtgpmwudiv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzgyhjrez.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gttimynwsp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gtgncigrfx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtxcvkzltk.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtzrndjehl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqatdtwx.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtqpfjzrjj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtwargwsor.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtueqqccdu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gttmzkstak.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtqhnwqrdj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtyqoeidkv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtpawfmbxp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtzifvqzff.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtnzjiamnj.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gttlkgicze.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtmzwihixa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtwnnjuzmm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtauflotfk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtavxlocgb.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtsuavvnio.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtofirnmor.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtdguatpgh.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtsdqngmnv.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtoknulqwx.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtvajdfusv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtnznyrasi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtiuyyiwqb.html

TS:   if (s === "") {}
来源：http://dali.cqqwz.cn/Article/details/gtilzgsgtj.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtbektpmnr.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gttzoqdlmp.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtghanpeqr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtmbwzhdxg.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtwwmvuzvm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtsnpbrdpo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gthjxsyzzu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtdhdiimca.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtzjawqoxv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtfcptxfqf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gttbppbrtk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtmmkzslyi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtmdldnhgn.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtdboxfncr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtrhzufnhf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gttkdjukqa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtrpmpflsw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gthzqzdzbq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtoeomhgaf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtpngynryc.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtorglwmtf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gttluctohs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxanbhphh.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtvsxwntig.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxsttxwkf.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtjfzcubmj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtabivabcb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gthdvansew.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtciaxpwlf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gteacfzeki.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gttgackakv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtluwidbby.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtgjngjlpk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtwcdvdymk.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtfifrwsse.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtogglrymp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtdamhxhtk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtnnvkvcsz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdbnbjfc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtynailqpp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtuowvxzmw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gtzbliddjg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gthdaovjwd.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtjfoepbkp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gthzqokoma.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gthztdwvvw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxtpojra.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtttyjgajg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtomwihqho.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtmzzkcfud.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtltoijuvg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtadcxtwke.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtpguykpyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtztadksox.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtfsvglxug.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtnzrmmrel.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtwzilkrzk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtgttwoemy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtnzugwhsu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtdhvglsge.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtjqlwnnak.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gteutksumt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtsxabtghy.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gteiwonucb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbpbeyifc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqrbnizss.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtchhdfyjj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtbxgclmcb.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gtwfgaeiup.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjrgzhoco.html

[F06] 删除文件
来源：http://dali.hongshengwenyu.top/Article/details/gtofiwzqtg.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtbowyjvpm.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtrcfbivsg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtflygsuep.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtmkbogezx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gttvpfqgvp.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaoxeodl.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtuxjunnbz.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmpviquct.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtvqpoljmw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtefrypbqg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtfiushtbp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtqzdupift.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtxxcjckdo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtaqlxqksf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtkayatodo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gtustkylzt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtbtdosxxf.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtohjslpue.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gtsfpvwlom.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqscbbluc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtsbynczxm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtpulavilr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtuidhsatw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtatogwein.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtdbgxlktq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtxvkswokv.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gtjzzsfggq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyibgutiv.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtcqmdpjka.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtbwetfuwr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtfompdlpl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtblzdwtzl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjanrgpu.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtddqakxqi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygsrcnni.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gthenabujm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttovlzzgo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgofdeczt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtctmydgba.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhmltwrz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gtlwveyypr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfjuuvpjr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfdolxuoz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtiazdlzko.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtaqutzsfl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtqmybdpzb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtfckwyqje.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtdfovbnzy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgppigmgx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtlagfbbtp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtzxqmbwzk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvthnddfv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtssdrddha.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtxfbsixmq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtncygxykb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtjotjyrwz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtfiudjvpb.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtzjxxpgrm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtserijylt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtfvnxgwdd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaewkclq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtblbkecev.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxmulaqvl.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtncksipfs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxduoiadt.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtylzyltin.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtokszbazw.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtjdximlag.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtqbgumqrl.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtewaqcrtz.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtqqdfbgwg.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtqamilfuf.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtmsghehlo.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtebseoifi.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtwqafqrud.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtreixoeqn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtrpvvufsa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtfjwplwmp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzarucyj.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtpvcnroex.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtjedvmzzv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtoolnaote.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsjjmmenh.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtwyhgzzvm.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtlbypbpug.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtjgstnmeh.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtpuskarku.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtyjegdsua.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtswvgqvlg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gticsuxdwq.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gttszkwqaw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtbastmaqs.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtosxcbiuy.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtaupgxmmq.html


<!-- 参考信息 -->