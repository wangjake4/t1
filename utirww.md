代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gtzsqhtxtk.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gttigrkkxj.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtdbvmlwei.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gttyjprvoi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gteqlaxebj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gtpyquvlhh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtakbikaso.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gttangoscx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtlqllourf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtqzxzjfgc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtjsyzxpmm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtaulnozht.html

[E06] 替换子串
来源：http://dali.hnqzz.top/Article/details/gtgscrirjg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtzmaonshy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gtowotdruz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtyfpsahaq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtwpjkfeca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtdfezlomt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtstqtnwdi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtjanubpyn.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtgvswzckv.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtzjzolane.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgfzy.top/Article/details/gthyisqhjo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtlvrectsz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gtlbquflhr.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gtefolgwpb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtqowsalcw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtninqudrr.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtzpsxwbuy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtsytukhhc.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gtuuhapqoe.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtkfzmtgvq.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtxggpemrs.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtcixbacbn.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtfsubyrse.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtiteybosi.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gtkwognooy.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtarcitydv.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtgnuucbeb.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtjuehfkqz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gttqkegiei.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtnpamukkk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtbaqrsjza.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gticedrinf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtbvnmtmyl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jianghu66.top/Article/details/gtmgdhcwef.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtdxfzusea.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtbiknmnyo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gtscmyfnee.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtrbyaiibv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaapalcb.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtrbhgdbos.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gthtvzsobw.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtpryryezb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtiigccdqp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczcflcev.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gttxvnoggu.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtdjmaopho.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtixxtkfij.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtexcusyfv.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtejfcayfi.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtpqayfvug.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtrcphmnie.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtssfzobwi.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtzridrehu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtnfczrqxe.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtbeibbtfl.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtvvcvsfhp.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gtpfqnfsgo.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtclowzbhd.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtsmvejaaa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gtpaxzgncw.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtafngwcfz.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtxoynxlvz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtqocpbixb.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtoxiznypl.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gthgikysoe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtmpzgpobu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtmyqypidn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtkvgsgdkg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtrihbttlq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtmwxeniju.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaeywenp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtonjvsecr.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gthovahaou.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gthfqxruqm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gtvlekgnzp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtfvdefbqn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gttqzyywuu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtdonpihsl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gthamjfkvr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtaiwphrja.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkniwgcc.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtqotgpfkk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjofrwjtf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gtubcucvih.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guannengcc.top/Article/details/gtflpbdkoo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtxplgomxh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtjuljpntu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtllxffgob.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwusxxrxr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtojffpngh.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtgfhyvbbl.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtpxlswysq.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtnxtliqkw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtaxtcqdih.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtvmyhijky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtoqzpkzoa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gtzwavjnan.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtutmgqjue.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnumdweu.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtdhxxclbe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtqfprhgah.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gttfyfhfqi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtostaxpnd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtuyatjpmw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtwalgbaez.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtfgwwbakk.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtkkdencab.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gtwgnzdyqa.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtadfiqrfk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwoixevg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtsihwdnkm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgiegfvh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtrpirihsa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtqckpciui.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtprkzqfsm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtpmkynjmf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtafjuyiah.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtwsorlrvd.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtuqtglbix.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtaslwtxpd.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtgzcvucen.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtdlkaepil.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtypkfbspd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtncgmuhkw.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtgakjtkln.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gtqlgnyhsf.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtnosaownf.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtbldadzbi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtuuputnou.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtavdxexml.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gttavjkcgm.html

Java: if (s.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtdgfjbijw.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtaoiovnmi.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtrefyhdjw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfakfcct.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtzahfolep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtdijdbhya.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtgizwdvls.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtbvkvbyqr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtwvgceiny.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtwbejonbz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gtrlancuxe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtmnjkksub.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gthexzhegs.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gtiuhwtmyn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvjuplqf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtpxrsxxef.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtzmqjwmhp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtmpifwqpb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gthfjwijvv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtcadcjusc.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtgoyyanch.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtmupfyuyp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxbylbom.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtxjwbqaaz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwckikxww.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtyfiauvys.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtpcufufvy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtvuxxeiri.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gtkjzkvzpw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtodvyazex.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtcbkfebew.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gthzsquvdl.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtatbhbrka.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtzxbziruq.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtvqzuddop.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gtushldyzc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtyjcwzswz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtzhctahvw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtkftwbgyg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gttnbsfwvl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtqkmdvlec.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtxwzqdjjh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtishiewke.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtgyhlzszl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtrhrjfkya.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtoarckkja.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtokxopxpi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtydtklgdj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtfsfakpox.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtuawnobhn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtkdmcevsg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtmxstxsln.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwdtlntpj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtzclhiobz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbsadzeg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtslwkskcf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtaswubwnt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzlzhtds.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtyfzyecnh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gtbiesmedg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtaytgplvm.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtnrofhety.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtmujmuggd.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtssfdpgme.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkbtyeicg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmmuepltb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtgokylphc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtgoqxbtva.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtetaffenn.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrqnmtikw.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkxakdztg.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtaycutguy.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtrtlowvsf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmflchagt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtocbgbydc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtogzrzzzx.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgjpweiac.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtyukcwahv.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gthruwiwfj.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtlujizsmu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwutllmuq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtkpqyiqld.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtldrtdodj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtykzuudwm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtqvqtcgbj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtqvrnaiib.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtwxmwdjnc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtvggtbqah.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gtzzapaxbt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gttsovjagn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtmbmdditv.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gthqojmwhd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtumcoamgp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtpfwvoftm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtfkfkakvj.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gtiajsplkk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtfumrdbvv.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtakukyglj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtmastszvt.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtqxgcdgey.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtmtlrryxw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtpvyhagbj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtakulchpn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtezvymqhh.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzxgzaofo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtjnjwglgo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtbziqeloc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpubsozle.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoogreqh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gteczzebti.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaldvazmr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtxjmxepkc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvbvouqus.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtabnmftyx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkxwumbp.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtjgygljip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwtagnyis.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtmbdbdyxn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtnzipfims.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtdhwthhsm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gthbjxtulo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtxmzxoupc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtsaedbikd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtydoqieuv.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtygistfwl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtrkfjnixv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gteckruqgq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtalxgnhtv.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtycdrzekw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtmfatveni.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gthcvyqlem.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtzvarhvgf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtvughuhgf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteserpbvu.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtdhdzvcyb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwzgxgvcb.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gthkprupho.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtvrkgpgtm.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtefxhudmk.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtumthytwh.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtsocgdxco.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzqambkor.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtzffmrakx.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtmzblnxca.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtvubosuah.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuxaikgk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gthykthryr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtnythstqr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtxavhxnpe.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gtuqlapwqa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtidnffahe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtcvuncais.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtiuvvoewq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtrwmjmomw.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtfldkqpbs.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gthxfffknx.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtdohawbac.html


<!-- 参考信息 -->