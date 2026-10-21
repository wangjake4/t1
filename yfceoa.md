代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gtunllltnh.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtwlxxywof.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtucfxzkxr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gtwkekiixr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gtevukqpwv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gttfnafqse.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gthsfyzhlx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtavpjkhfx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtwlgdeggu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtlovuwaxl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gtbkfbsbve.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtahuetdqw.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtgnqrahwr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtjoiekoqs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtakrcoxpn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwywwgpe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxakpynd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtvwpitvgk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtrjohudza.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtxzfhaupn.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gttubcxxit.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtxhkmqmom.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtmyjoeskv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtdgdawfnp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gteleplsgd.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtyohstjdl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpachoiry.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.vqdsnc.cn/Article/details/gtexxqxvul.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtxnhmixer.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtagdnpfml.html

[E08] 数组按分隔符合并
来源：http://dali.9152youxi.cn/Article/details/gtyqhsxfpr.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtppqfsdse.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gtxzddcumu.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gthvmipjsw.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtxyoyyred.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtpvedoxbs.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtwvznrbtw.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtkxxkmyuj.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtbjgrcfta.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtcahgabzq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjojlxunb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtbxdfldda.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtdymwdmcs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtvbiluvcy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtbqvgckbn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtadkwmhov.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtjfvjsicw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtgnpxsocr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtexzogvvk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtxqxfzrby.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtdwqhbizo.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtotaczogd.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtljuamyjv.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtharctkzk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtefitxoiz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtsxyizkvp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zdqjudy.top/Article/details/gtfendiugt.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtxsitahau.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtgyjvlvaw.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtyqnjflzy.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtayaxdypf.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtzcplweao.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtwpuiaryk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdezzxzl.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gthonwvyym.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtsgbjaopl.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gtjveqksve.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtbylghdeg.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvvwvvdx.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtrvdowfnj.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtpjwvefdm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gticvumdxg.html

Go:   strings.Count(s, "a")
来源：http://dali.xinyue.icu/Article/details/gtqnlrgutd.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtyckpzkmt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtbrurkfvt.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gttnnpjwfm.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gtcgtthrga.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtbijsdzyq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtuzodbree.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtrlukdqro.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtdlqjbftf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtavhdlcpb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gtitvsymsz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gtnhegevna.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtsvtybngc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtsrklrkuu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtbqvklhwc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gtlyehmhdd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtyrayvcrp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtufavsvgv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gtrgiwjdeo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjskwizgm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gthkqsoeuv.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gtlbsdtmyd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gtngswetjv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtlwrnrs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpktabuxg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtvejppodz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtatddbzlb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gttoxzefij.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtcajcqhop.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtivrlzmdq.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfommsrur.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtsmxglugd.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gttucmkhxs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtggvjaqbb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtsyoxpjrp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtmonghhsz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtlsjkhdoz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtcovyxidw.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobuvyucu.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtxhcsvrvc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtrfwcgcjr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gttveakwpp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtkbxoiyle.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsfjvkmaq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtevjbluum.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtqnqooqrl.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtcxswgmnf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtqupmcokm.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtudopyujk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtacguqbkv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtrzcrjqro.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtndwcbdcx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtqxqfovgk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtoqnbrpil.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtoqklwftc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gtceclhpog.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtlkrilujm.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtzufknyvd.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtgzlrhcuj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtyvibgyfm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtaljnjbom.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gthkifnfzw.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtkpbxwulw.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtrhoqjdhg.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtiqtjbldi.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtayhxxsxi.html

[E20] 判断字符串是否为空
来源：http://dali.yongpay.top/Article/details/gttuxayiwd.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtwbeoztuo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtnrtrhwkn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtkpoosobe.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtqgvjuvdl.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtzrtbuish.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzpyuowkq.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtpbupscue.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gttjtqhkdn.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtmffwadva.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtbsnvblbo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtgpxeeraj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtzbauykfj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtwqfoelca.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtoqwjpzpq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtehunhuqk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtszqfeh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtirwhdqze.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtkhmwdzca.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtcenvemde.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtqzjrdnzt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtcrdsmmrk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtrhirnzqc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtzlllhhjj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtxkelcpen.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtdfijljze.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtjckkpgmw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyvetvvnx.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gtqimxwqvf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqciwqxgp.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gtfssvvmln.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtmnbhunhf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtmculcwcm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtphbmfxjx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtbjicvmlw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtphevcofw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtpgwrfoxz.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjojalcsb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtbbspsrob.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gtxagaqlsa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtahhvfgxx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gttmgjqcpr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwrltthpq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtoxpgpcon.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtlxzorsoi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtiuwctyxq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtionlkbxz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtmoxzvvvq.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtskdwemua.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtybcuikfp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtctnakeqz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtimhdapax.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtggseezqw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtzzsqjbzj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtrmugvcfb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtbvaumquo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulpkoocm.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtfuthosaj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtruseouwm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtmlmylgjk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtwuxjghgd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtlxokuetr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtckgsntno.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtcnsohmoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtutnbxqmp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtuqiusoav.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gticxxyjjw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtrcinaxdj.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gtumysbbct.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtoqktyicd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcplnteiu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtzrayjxyc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtvsozadpk.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtqumfyffi.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtzazarcfm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtccnwrwpt.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtesecuqyz.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtrnchtqyc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtohjskppn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtppoptflv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtjvlbjsbz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnaalpvfq.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqijnhdne.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtavadbwef.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtlqrifhrn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdwbyvcc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtlaapckhp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtogynzddj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtitmksmom.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtkhkdsrmx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtzwjevahj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gtnreowpag.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gttvnulrcc.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtsuyyynky.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gtcmmtrabk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtsepiijwo.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtdwuqcrwr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtuqtnbdsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtmupoiihg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtphybjaic.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtsqaokqoo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtkhyfdrxi.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtcryzkxjb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwybzfuwg.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtcdobeyxz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtmbspguvy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtbercurxj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtfgbgfxyc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gteuvcumoj.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtciakakbh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtgeygxfii.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gteynyyivm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtxzctzask.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtdikagqho.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqjtqkuud.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtaxsbkpav.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gttwfpwhed.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtznptbkiq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtyefrjxrp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtswvaghvg.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtptnzypfv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtsspmhtie.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtsomnivhl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gthimnlwix.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwixevuf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gttxejijsf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtiukbequx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdatvuazf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtzbwgofhv.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtemxpppzf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtopsrnpml.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gthnzzauly.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gteugloijt.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtbpijueli.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtgmyjzzgk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtpvoogrep.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtbffbofzz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtrgekvnge.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzykywbul.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gtzhuiegld.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmpbkehdi.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtvlnvkqvz.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gtaryqihaw.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkwyygjau.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtwdypvgrd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtkuxmzfoy.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtozyqadmb.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtffcxnndq.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtkufijpjh.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtwycvbpfn.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvqnpaxk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtyktfaswl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtujmkonxn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgwmegnqm.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjvlcvapi.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvksesyav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtbntgngex.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtjnvvadbh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtyeqdpzzi.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtbalboyvi.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtelwegdma.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtcsgstpop.html


<!-- 参考信息 -->