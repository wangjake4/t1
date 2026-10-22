代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gticclvpvx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gtfevuxaci.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtlhhubwcv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtdxhryaqo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyudwjhu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtbsdxmgqk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtrhmbfdfn.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtusjjwtdd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtplwisghy.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhqfjrva.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gthncvmjoy.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtsuepszxg.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtqjdsrebe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtjgxltyaw.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtqhabvusc.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtxknywdqu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzgyptgcs.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gtcyoldpmn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgkomypnj.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtaqdqtxgx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtviigeegs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtgfwtuggz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtgofqdfco.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtqhamppzs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtcpuwykai.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtvtdozpcr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaupycztd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtpxvdpdng.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtutlpxfwo.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtxsyhfulv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtkahuiyos.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtvrjrklvt.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtzpyhypyq.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxrwdlxc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtvaphcwlv.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtezlgeiid.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hywenlv.cn/Article/details/gtkzhqsieu.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gtojrvqfoa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtiifhicbo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtccnvpwxc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtdmctcsst.html

TS:   s.slice(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtulammyxq.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdechwtg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gthodguydh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gtjbzwuemn.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtpznfxckz.html

[E04] 查找子串位置
来源：http://dali.ybcxt.top/Article/details/gtoleatqnn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtvtcohwim.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtermjghhi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gttezbsrtw.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtzymhkokx.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpwkqalt.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmcjatna.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtzjlbqrgp.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtaqlfcaxq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtwkvpobxm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtnybelspo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtfiowonmc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtkmelssew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtwtkjtwcj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtgzkktrbu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ehwqpu.com/Article/details/gttzhnpebv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gtvjukyduo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtjargucxy.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gtutuyntnw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtedznnmcd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtipqtawxq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtmbgjvfip.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtwfaakgit.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtirhnwtcs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtouwqqcko.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtofuffhxn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtxkzathar.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gtgvjnazok.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtxjkqoeua.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtywduusov.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtkfplryik.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtgznvanmw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gtatktynwu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtltilgcqi.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtxskxuuvq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtomjbqyew.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtknltcduc.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gttrroiqlx.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtbgwugmpm.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtfzcpfydx.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtyoybdtyl.html

Java: String.join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtqfxporgi.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtpytcescy.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtxehwgl.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtiquqqjmu.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gteawyghua.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtbzefjamp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtkmbylbln.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtybjpbgdt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtxcidnbjj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtkkhzvhet.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtxxrfthni.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtzywgzlhf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtuvmgjmqk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtfifttdja.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiliklyh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtuzkqrspm.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtjhhyavqo.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtziquwhib.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtwyjusvod.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtwstbzcoh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtmxkattud.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gtuwuknrcu.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtjpfsbglu.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtyljsabdo.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtyfhmqbnn.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtfekzgxhq.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtlodrpzng.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtnudetpyn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtwntaxqio.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtauzyurpz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtjfymxhlt.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gttjxidauq.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtfwfpuygt.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtyqwirzbz.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtoipoyfer.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtlrfthhjr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtnbjpwnmt.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtwxavjaos.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtnpynarnz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtqbrmatdr.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtrlescpxp.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtaylhbcya.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gthivvodzl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtxshlyxmf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtaqzpxoqs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gteaexeiir.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtxecrvbsf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtrguouhlr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtsjnrxqtb.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtnabybpre.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtgjpjeypj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtsmpllepw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtcwfsgmoe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxvdgtia.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtuquwssfr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gtfucttzuo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtmcqshcbz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtymzpbgrh.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gthlmzlivp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtgzlmrulj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtqtuigdzh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtjohywrfc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gtqbufawds.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtkxhhtntf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqutvwasj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtrkfgobwa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthshkcejp.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gttckmlngq.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtsgnjuscf.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtaiaqlsny.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtshyixgxr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtkrhjkxvq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtxmavrvhr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gthwwehoym.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtuponhrco.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtoidzzmud.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtkzklbbxt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtllcuuynv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtqalgvgqg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gthurtzpey.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtqlmvrbkk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtedupqczi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtojwxtldu.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtsrxbyjje.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtsmfiiqrx.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtwfkxsunx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtdwxvmfae.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gthlkmvhis.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtoffztxyi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtvtsucuys.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtfxyhucqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtnjcokmta.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtjdpqzvkz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtdvqlcznx.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtwxpewccp.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtvpkjjmmm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtnfkxfwso.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzujajjb.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gthuulgivr.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtzzyqasmg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtuelrlgqu.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gthhjwgkau.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtfcnmjmcd.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gtpmvupknf.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtvxeydafi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gtabrtizlb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gtrxyevcnn.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtgrndjbih.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtixddctak.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtxbjvilkh.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtiblldxno.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdmyeztwe.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtegcbsuku.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtmvwqozoc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtyogfdtlv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtuudpggny.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtznkbjuwy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtuxprohvj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtjdgwrqfy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtehcdkmol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtxqlfjjal.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtwbixnbcd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtpjqqgrdj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtnccwepif.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtacxggetb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtvkegwnqh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gtldxcsgvd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtexvbkhex.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gticoshpee.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtbsmnnrgz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtocwrchjw.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtkiiqqeoq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtixyvfefa.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtonfhiyxj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtadavacll.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtpsndfcmq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtmlnfpdsh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtbvjxvuyx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtofxqpskf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtmhndkqtp.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcibtjrdv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtrvsjxmgx.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtjhluizph.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtoqgffbda.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtbzykodpw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtqlzlhkiq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtavalytuw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtxkpthnxq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtfnxgdzsc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtfcegdduv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtzvoqdlwl.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtzbeiluwr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtjwxabkpc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtqzgsyrzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gttdwyalhf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtockxjovg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtvenjqbpp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gttujlnymc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gtoccxphxc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtteyxndom.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvrluxhx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtkacdyqan.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gtrtblyjvt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtguyshemp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtzjypynge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtzwbwsnal.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtlmevcads.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtmfhkalsq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhowclvb.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gtfkwoulzm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtfrhlcnhx.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtjlqaipic.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gttxfdxvjn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtikxlgmdl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtlzuhsckq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtrupzlizx.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvmywfrzb.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvftbxpez.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtmdmeaytm.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtvfrvhrnl.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtfdhgbpyq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtyohvjfxh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtemayyrxu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtogwlvejt.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvipljmfh.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gthfmnayml.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gttljxbmfe.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtsmgqldiz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtjtqdfdgp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtalrmjonw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtuorutvxb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtzlstzbie.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtideyhold.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtvmrrjwsa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtawkxcprn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtpbcpblah.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtcdzwlsio.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtixzjhkjd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtblkigsrl.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtvqaeqjyi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtinzximae.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtqypigeud.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gttxsckwjz.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtbkjurolj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtmsneinca.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtrhwlflmm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtzpkamptv.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtodmegapy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gthvwtnwfn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtaicckuui.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtthvmuebu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gtpeljvacb.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvscenpqq.html


<!-- 参考信息 -->