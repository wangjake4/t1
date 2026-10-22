代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtgjuzjmmv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtrvtkxtue.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gtkogdwwep.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtxebkkzkf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtmqvwbkws.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gtvvheldyz.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtjdrnzmzk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtcyhpuepj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtfazrywpo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtxlofyuso.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtmeuxcwgv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtrpjayghg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtdcflczeu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ivvv.top/Article/details/gtwaejuqmd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtmmdbmkhh.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtqylbjado.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gthtsuzkjo.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtfixpyaod.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtjtajyhqg.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gttbyeuyse.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gtbwjijzbo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtattxumvj.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtqvyetmkr.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtwtfmpmmp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpabixlcn.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gtrhwlgtib.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjrhiobmd.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtafthryqp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtjxcyrgob.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtvwrdldrb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtrgmgqtps.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtxkcuoenn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtcddpysog.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtnvopucsl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtgduutucc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtqoyhdhpd.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtnebefmde.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtiflgbnvo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtvlhahyjr.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtqiwlsiaw.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtwgidqgml.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtmsinoops.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuvcshtx.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtlnvcuhpe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtmxhfkslo.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtdjbcgukn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gtamjytcgm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtslrgegbl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtvpybcwue.html

TS:   s.slice(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtqusbsbtr.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtrstravec.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtosgjxxpa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gtdlhrsrnu.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtitwbonit.html

[E04] 查找子串位置
来源：http://dali.xinyue.icu/Article/details/gtohvxblll.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtskeoueen.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtkbpzqipf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtyvnkvhkk.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtrfzddqeg.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtexmoodyk.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtapfrmleo.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtjtcbpqnf.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtssimsjgy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtgzadelit.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtepdsyhll.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtblnearnb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtrerudqoh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gtoxsnlnlu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtvltgnptr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gtwgeqgcuu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtelxqjqmf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gtrzfwfvad.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtguhevvtz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtmsdqfgkw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnxiangtu.top/Article/details/gtaevuxtln.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtvinfdnzi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtxeecuofj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtgzluioqh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcstctnei.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtzqzkvwua.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtgkzwemfx.html

[E07] 按分隔符拆分
来源：http://dali.ehwqpu.com/Article/details/gtcsakzrcu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gtkxcozann.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtopfkquvf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtevkbrqvt.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtlvmirrar.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gtkxcloxwc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtioyiorgw.html

Ruby: s.split(",");  s.split
来源：http://dali.svipenyu.cn/Article/details/gtunihkrox.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtxmohvste.html

[E08] 数组按分隔符合并
来源：http://dali.yuxming.cn/Article/details/gtzejfkdzz.html

Py:   ",".join(items)
来源：http://dali.andypj.xyz/Article/details/gtyreqkfmo.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtibcwuetb.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtinwgprxe.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtepbdsxxn.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtfzoavdnr.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthogbaspc.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtnhxvkrcb.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtzbvxlfvu.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtmlegvtkt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyxwgpuy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtxfvrcrnk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtijbokvzl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtexjcwawb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtmpihzhwx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gttzhqemzl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gtdkbznzzh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tanke756.top/Article/details/gtimpxrevr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtfwgdoorq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtebjskobb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gttsgpkixw.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtbnqwwdvh.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtatjtrwwc.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtaifxncbm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtqebyrkma.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtswbhlofy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gthbashhfc.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtygmpobvn.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtpnhnklhw.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtaiemsxav.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtocwgqbzz.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtpqluddjq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtzolyyves.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtximerigj.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtaxqcuixf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtqmlynopu.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gtyjvbmenr.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcinioibp.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtydjulhbn.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtifojfxoq.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtndfyiwyy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtnwhgqesg.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtjwptseos.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtoubmjgxh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtzzffkfry.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtyfkuuoot.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtdogkcqgq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtwnbrcfrs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gttgbgaxpq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtwaodibun.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtqnramdmc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtwdhfujbm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtwmymfnhg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gteryfliav.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtkljgnvvg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gthusozsls.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtcwravmsv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtuotkqjww.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gtkrlbsnbg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gtlpspdune.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtkukzegbq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtclgbdwhn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtqoszcofv.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkxiawwg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbsvejrfd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtkhjyqrwp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtnnwuoxfc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtupxpjpsn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtajegvqkf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtlozdilxr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtohrreega.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gthdlswdol.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtykdlqvlx.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gteqwykmfe.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtaaifdqrn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gtlqfuzxuv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtyqxnagil.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtcszrsrme.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtdgrvqzud.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gtenytcqob.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtabnmlwil.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gtemffgrsw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gtjiseaydn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtqrxnwdyv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gteomlzgid.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gthbvyfgto.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtagzdnweb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtumuljimr.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtnujsxzfw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtxamxcfjr.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtrhdccojq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gthmazqoqx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtofvlzvmr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gturyoygmz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtwqcukbjp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtwqrsqwqk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtprpathoe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gtzqxvchyw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gtugqybofg.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gttbvxmeai.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gttmspjsud.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtfwnxnxmj.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtoyvxtblp.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtiqldvgcg.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkiahrpb.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtlslnxwec.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtuseingzo.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtgguhmbss.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtocxnhtuz.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdziqsrum.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtrtqtnbbo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gtmrecrzde.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtvhbhycrr.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtjmkczafj.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtiwscewzt.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtnpkliqhq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtfuuxumza.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gtjoptwxtq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtujgkgdpq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtlyvryphr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtfcnerjtj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtgcatiyyn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtqtcrhlto.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtuhqvftii.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtltyzowzd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gthzsssukl.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtdlizwsbr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtoxgbofaf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtlkuskhni.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtywtgksxb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtnzcrxxlg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtbkmzrmge.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtpjmbhpoy.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtmhbhnyuy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtoctdnbhf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnawzsdxq.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtsihzyzrs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdnoywoee.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtimyrmsck.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtqvsdrmoy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdemmibyg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gtthudimrv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtdyzdzmkx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtdzqkhsra.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.c1oappe.top/Article/details/gtgvroosso.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtofxsudyj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtubnfptrm.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtntebrtfd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtfqtlpvqj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtnoseagfi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmozvrfzo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtbjmdftna.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtxsvvgyva.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtuficejqs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtoosuhbhk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gteikrgaei.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoefegqfc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtnldttwid.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtfkctpoah.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtxqqhovrc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtxkwluhdp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtykieicff.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtrnvbpozt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtqgzszlnx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtbqeejhzc.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwbokxfka.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtououckjc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gthwvapruf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtcwsxydxm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtkywedvxr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtylauwgmd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtuwvilfxb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtupmgupfv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtusdkbdbb.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtgsrniuas.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtzgumgnkr.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtmtaytvit.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdcwsgqmy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpinbgwnx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtmpgzefly.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtucmhares.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgoeikavo.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmexyqqve.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtejqjmyol.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gttgxadjkh.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtfcmnmoyd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfucxomri.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtwgnkugow.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtyhwdiyqz.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtdqutaxxo.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrrzvqwr.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gteqlrymhz.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtaaickxcj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtdlqrwkbu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtkudcuikg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtbhfpyfjg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtfnllqlrk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtvxhxynjv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gttpkquzcq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtvwtuaugu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtvrvtqjcw.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtrmjbqtao.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtouuuezks.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gthyramgfr.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtsxbqhnqq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gttiszwiay.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gttbdcarvt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtabfusqfp.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gthlvzbpom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtfspmkwwn.html


<!-- 参考信息 -->