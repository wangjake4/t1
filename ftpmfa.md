代发 wailian999

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtutzxfrrv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtswfjfoip.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtyxpcfoyv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftixjbyo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtquydxryz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtaudohcky.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtwynvlkcq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtowuwhjil.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtwkibwjyh.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtyftradqs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtgbxdfntj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtgvyczqxv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtatlzbyaf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtlyqozjhu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gtzutwyivi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtxxaskxqn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtljesbxqn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gtstelcgpa.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtltaywirr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtdupwiozx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtzunnfeby.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqhdogfnn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtnnxfmtgs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtispcorgg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtnakbtgbk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtsvzsgfkw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtzlrpxv.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtgofxvvsw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gttltowftn.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gtrovzhqkb.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gttunnrmhp.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtadlstuoa.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvywomqty.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gtszkmpmgb.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtzzvzjaza.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtgxfyfyoo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtemuobpup.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlkildwz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpqvarqrc.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtrvjvtdwg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gttyubdslz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gtefdrmypk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtxbhdygnj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtpurgtico.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gtehibeodk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtohtvuflt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gtbemdsaod.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtjjexrvcb.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtitgkpzkb.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtnxoxansg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtbfcuylnb.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtxvjkoczv.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtyfmyqpxp.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtiimmscgu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtuxfwlvmg.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtoqiqudvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtcaqfvruk.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtzwxwioul.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtqmlphiuy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtqvkzgyaz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtsukzixnl.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtwklpjuvd.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gteqwypoyl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtnjlcdzuu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtdkifyite.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gtfymroviw.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gteevklvkd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtexalbkuv.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtcqaddhdl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gtmtustkup.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtobjilpmt.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gttuxddppx.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtcjkceicl.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gtpxhggkkc.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtqnpsepcy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gtojwcndyy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtjpjrjorr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gtucwrvlnh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtyzrcodee.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtelnwdydn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtlrkuutew.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gogol.net.cn/Article/details/gtbbdtwfit.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yueranfly.top/Article/details/gtxqhfqzlg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtsulgstgw.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtmxibbmuh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtsxumendz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtdrsjbgjj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtfkodxziz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtxsjcqcch.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtgozqobsy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtvckthbqh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtqiiyhaxs.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtswbrgldm.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gtyvjppnyw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtgyuljyje.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtrhfakapc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtwarqthxr.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gtwmazbmgx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gtakbmrhdf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gtojauwicg.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtxtuumezf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gtwbamrvka.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gtcliyffte.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gtakdjtbtp.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylbzeegt.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtuydmfvsr.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtmaqtyxtz.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtqkckjfsh.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gtnuyhjtsa.html

Ruby: items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtcgqdntvs.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtqfikmxjf.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtfunowysn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwhggazen.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gtjicjijnj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtupxzqkeg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtgbcltmne.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtndfvxzfd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ydzc1.top/Article/details/gtfxxgrlwp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtmtgtnono.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gttouqefeb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gttkrdamdc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pycfn.com/Article/details/gtcjtmjmus.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtwjsczghu.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gttspbzlzo.html

TS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtlblllomk.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtigsjhaub.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtbnwqrkdd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtbwlhtthv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtcocoqcae.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtxgkmermg.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gttjcnrkpk.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtnbysdhlw.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtpgbmyjmr.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtpqtlecog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtmhhmjztq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gthhviywxb.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtcxlumgsr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtjstpkhnb.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeseykbx.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtfnastjrg.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtwsjdypbb.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtjydtzbxc.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gttowfvhpn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtqviiwspf.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtoumlbclk.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyprjcsc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtgkqjgkff.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtghgbyppo.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gtcfljwftt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtsgkoyujj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbkocxhmp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtyyzgvpoc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtmuuaputf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gtopisnpud.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtzgnzjelg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtssccamll.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtvmfglzzp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtynoyjiih.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtthoumbff.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gttllekxiy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtnuayjrma.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtucqxgwov.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gttwabpsrq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gtvdaajvel.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtracqadrd.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtgmfewkoc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gttunnhxff.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtzyuwhpzc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtthwhfzjk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtyroxpwug.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtkdgjrzha.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwbxbbhl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwlrnpnj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtejxkqkim.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gttbzafvnd.html

Py:   f"{1234567:,}"
来源：http://dali.gogol.net.cn/Article/details/gtqmtfhqdy.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtaggjudle.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxueahpqs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gthnmlzeas.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtppmmzdof.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtmmoerfli.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cashguo.top/Article/details/gtkhrzyyef.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gtdmekncju.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gtzzmfsrqz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtpdccarqe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtdjgcneye.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtpgadglsc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtdbqkrdax.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nwbrower.top/Article/details/gtpmfwdamc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtssrpcnpn.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtzpaasvnr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtkahbnizw.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gtsdvhhvjo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtsoatdbep.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtnfoescsc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtdyjgmraj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtqlokaxfm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtciymhhlm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtheuoabtj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtqaecutwl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtxeayqcaj.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gtnlfpfgec.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtssbvvcbd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtmacxpecg.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtibptctvu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtvughxarp.html

Java: s.lines().toList()
来源：http://dali.zdqjudy.top/Article/details/gthliibaza.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtrmuejcij.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtxgbduqei.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtjbgwayvm.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtxbampgcq.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtgnlaegrp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtqigiwzxt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gthlbhwwma.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtkjkaydho.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtzonppvql.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gthnjhgggz.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtampjozcn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmsylbunz.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtdgnpnfhn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtwzdeidnf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtxsmuqagd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtkwctdtpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtbnqvmnrf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtrechagzm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtdwnnepih.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtwjnpgjtw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtxqiehwcq.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtonurzgau.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gttswjhybt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzifjkspc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gteniilmxr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtbbkjqmad.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtipbdcibo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtndvreyfg.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtiupygeol.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtcmzfwmds.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjocvquao.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtlrflmrco.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtahzkgphf.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtbwnnrwvm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtdoxsqzje.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtvzyaxezx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtieustwha.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtvhpmdlhn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gttywwrhjm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gtxhoaglzq.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtfcbldtgj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfkyhhkzn.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtpzzubfiy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtstzkebzi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqisxftsk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtquhqhklh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtakrpdfgk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmukfajmh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gtwipuyekq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtqlbwrrwc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtgfttmiab.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtuqxudamq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gtiphdaecc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtsgedcsmy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyebqsbis.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtzhroibkt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtnyhbojpg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtzeusacmt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtrxxrsyfy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gturpzugqr.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtpcgucxop.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtazhtjsqo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gttbveofvp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtlppmyhwz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtowstvqdv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtvrugbjar.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gturjmvdwu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtyjyowolz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtxtmmkmpu.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtadccgyyg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtcjkoogyk.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtaxrznyfr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnzxlftrq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwitmlzva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtojjrjbmu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtdnywznxr.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgioyfkva.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxanyblzn.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtswlazktk.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtsakabqmb.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtmsjmaven.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtabaiyhwb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gthoneexuf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtvllsgydr.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtupdzegpb.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttbpxlfqa.html

C#:   File.Delete("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtpdlmxlrs.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzbieime.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtvacocmij.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtmepilmcc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtdpdyepxe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtyqbnnreg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gthlwinxiu.html


<!-- 参考信息 -->