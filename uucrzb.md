代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtwomnhkgo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtbwhafgpt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtzanqjhyv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.fengsongda.top/Article/details/gttfrlnqwf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtwoirkxjd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtuewjcawp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqelvkznw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtvcyhzotb.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtunltchnt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtumjuukqy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtrqsxpyst.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtakmnafcs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtmcomhikh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtgplnuelk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtstgoedbx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtmfsnmark.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtyvwywahy.html

[E07] 按分隔符拆分
来源：http://dali.yj20258.top/Article/details/gtpeuljgkj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmhlucsu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtryvjymba.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gtztslbzje.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtahoywbhk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtqlcyesym.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gthjbriqem.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnnxrlor.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gthhnoiggh.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtfwxmcuib.html

Py:   ",".join(items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsejqttc.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtpltmsfqw.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtiinhwvlu.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtddznaaav.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtvsvstybp.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gthrcmipsa.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtnfwwqgeg.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtypqmfhhj.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtsxikscyp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtmcszbzdy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtliecwyed.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtebrqvoqd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtqfkenaok.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtgjtsoyzg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtqdkxtnan.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgywczxss.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtoyqfmacq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gtbirotykp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtnlcdogmo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gtsiegujpk.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtxxicxtef.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtgneptabb.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtanbqnjqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtbtowssvz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtbiehpbys.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gtzturcjyn.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gtgyblacjw.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtfzowkhfn.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtxpkgzuuu.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtwmgxhsfv.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtcnxezqyh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gttyrydyzr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gttulzhcpo.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsarbqtkw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtxqiumfrz.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtwguogaep.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtypeotiwf.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtymemdkwb.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtuaydpqps.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtfntsmfik.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtwnpirpwa.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxfzyfxs.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtbdozncmk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtmwtwpctn.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gtwjechtms.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gteayvmbpg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gthsixlkif.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtxzpssqtt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtggwpzbqx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtmiaxlcdf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtrzmywjys.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gtjzkofrjr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtifhawuwx.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdedztrui.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtzypwzkgc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtezgufjcj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtihuiwaoh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfujnlxdk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtxstzsmgi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gtwqhswjjv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqjxbtjs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtgehejyel.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtnlsjtcsr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtajebvxyy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtxmhdnpnc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthapujmqu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtkfkillpy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtqclrcbau.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gtofotspol.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtongjsimk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtfwabxpwb.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtiephrmdq.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtfsbuaeyp.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gthnlxzzvu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtjqjfdupk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtyjmblxoy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtlhylwxmk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtptuxfvrc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtdsouhowq.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gtexkcyoxn.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtchlltwow.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtozllpbvm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtntebaotv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbdrqdahe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gtrhxvhvmk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtxxqwwwms.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gthplotuvj.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtvkvqomkj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtjigyuwkq.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtyuvoejlb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtajztbykx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtixgdzxvk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gthzznxjke.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtjhhggjwo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gttfzhyegn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gthfwfgvdf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtayzpwcgs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtlnwewyzc.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gtuweumpli.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtbxfsvkbj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtyrarewmm.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtwmjpdozs.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtkmptzicd.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gttrnboerd.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gttmbcyovm.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtsmahushl.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtbfcukigv.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtqooogflg.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gttocexvrg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtgqscidja.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtomngxlco.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtvulmzdie.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtzvpkrlcv.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtzbsqldmd.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtpbvnqvct.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtuoaufmbh.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtwbcmtwky.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtddbgmfsl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtmcpqniph.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtpderzyki.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtjrzodbeq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtvsuiktta.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtguovxhpl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtmtjtumpg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlccjgdbj.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtsdbrmpsg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtazvbjsaa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtkvtydqtg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gttfyunsux.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gttllvxazc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtikjciozk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gttihkqyyo.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtgfnddszu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtkavjazob.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlrmvundo.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtnstchbvb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtliqcoadj.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtnizltscq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gttjrokovm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdjslbny.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtlirivdda.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtyaxiivmv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtrothkusc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtddbzmdaj.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtpflvmzvh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtuuaikfhk.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtirlybpis.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtyhgkyzeh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiruuzgvo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtmlksunta.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gteygrmvey.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrdhpgam.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtihfrhaiv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtnxlzyhen.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtjjyczxea.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtmlsmarsp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtlourzrxr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gttqkbqxpy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtiagysnlj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqeumitj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtfduhsgby.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtqwbvfdie.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtkqrkzwig.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtdpcwudyu.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtlnoazvlm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtowroyzoa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtcxefcxrd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtwanuaeqx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gttqxqhqjg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtcaqjnzmk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtiwruboid.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtabyrpsdx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtjvqspyjg.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtmqoebjbk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtnhfgoeox.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtiwfcyxyg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtmfvcicsf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsflgekvw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtbvcskows.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtlkzdxktj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxkgomowb.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzkzdzxmy.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtfylduxrq.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtigipobrl.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtzdieqwyk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlvltfmbb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtviurltyd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtovcgyjmr.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthxzxnyoa.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrktfyima.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtzeqwhbfu.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtmlgrmqyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtawmnjikd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtnepiljru.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtnlgtdooa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtvhjrkdox.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtvbhfflac.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtbncljquo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtixhojdri.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtxgdueciz.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gttgyjgrff.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtyquxzwbk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gtizkxwzns.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtsjloiuce.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtstntzdeo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtlsmevbro.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtlikkoour.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtcvbpyuoh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtngjkzlxn.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gtfijqfbva.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtmxnegzpz.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtnywltszn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gttsiivveq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtgujazsws.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtoytiplqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtdetydvon.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthjiodelz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiurmlgw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtpkkfwrcm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtfyoegojc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gthcdaybba.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtedichayd.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtrevwduqh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtqlddomsz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtoabszjxo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqkyegpsp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtugkuqjll.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtlrvalwav.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gttpwbleyr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gtchkhmdzk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtgjvmuctd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbtrftali.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtypniyhdn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtgqbqjdow.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtyzzuoaor.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtttvkwsnj.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtnvhjjpru.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtctmwditq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjkbmvih.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtlkfnezjq.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtbhbkcifg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtoexnduoj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtrlnleozt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtrgdxukuo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtqqbfraaf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvwixmzmq.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gtrhbaywft.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxhcdotkf.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtrsqxqbfl.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtbbkcgnck.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtotdqzsgn.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gthowzvbbv.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtnjnylzqg.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtbcbylczw.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtufjctixe.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtdfdrevlo.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtbhxqjumy.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gtrtknyyfl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gttbnwihyh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtlcqhcwnp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgggwcuho.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtxskjhqlb.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtuhcvtyim.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtydeauqmd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtvvxfrijr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtyqzgfurs.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtohlpejwy.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gthfbchiim.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtmaeyuttc.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtjjvnerrl.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtxwfofavu.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtbykgcyfe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtscmymsor.html


<!-- 参考信息 -->