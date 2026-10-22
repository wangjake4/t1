代发 wailian999

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gt2vpqbtmfc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gt2ohebjrri.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2gutdszdb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2ecxavgez.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2ldzjbwpu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmsbppmb.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynfsmnbf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gt2tgufgtgf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gt2flefghxn.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gt2erbosdsc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2uqqlxhlz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2lgcdmnef.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gt2ylvkbaug.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xapnihnl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2asqfgczb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gt2wpdlmqms.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmdsmttj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gt2fptrqqwm.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gt2cyjmecga.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gt2jozdgpxq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gt2usznejrg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gt2jsrmlcug.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gt2qmhlbimp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2dreptxev.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hioaymtj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gt2tmjfwemt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wwseslvp.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2zebzomuw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2ijknvfma.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gt2fcpfjmrj.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2shefpaor.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2fpnqtdcf.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2lazvekyv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gt2jxmedtah.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2hpztcsog.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2twasgqum.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rwdrfqvu.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gt2oolzqclp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ziwpiixl.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2hsqnnuno.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2mpwxiqjw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxrphjqi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2gegjeowr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2fhoppwjo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gt2fuxvuing.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gt2oiswjiud.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gt2bbohpkvb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2jagvtobr.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gt2uasscyaf.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2bcewelkh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gt2vkzhycgv.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2gowjlmmc.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2emptjsqj.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvopxmeo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gt2hdybsfiq.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gt2qpoohzut.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gt2vgjqsebd.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2bpopihrd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2pybizjll.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2tfsqykxf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2qzdvqhth.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2jafvatyw.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2epnnsali.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2lnvaysdc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gt2iyvoggep.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpooeipk.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozjuydvo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2osyjfgsp.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2wjqkjqoo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gt2tenkprdc.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2rxqwbnee.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2fspkifbu.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gt2zofelcir.html

Ruby: s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2leqofdee.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2rmadaafw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gt2fowvcfxl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xuanzx.com/Article/details/gt2nkqvdswk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2cggmvcnz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2llvqygyk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftgcvjhi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2hymrxwbl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2emhccbmp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gt2axxdcddm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2tgxaeufl.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgvuqvqp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2syxjezxa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gt2bviussmc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzpkxujv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2yrqxcupt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2ofyueabt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfgiwdtx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2ztaolfzq.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2clmtnehl.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etapjoql.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gt2bmcwzwnj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gt2jcgpinai.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gt2dopwuveh.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gt2luuurybj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gt2lujvbwso.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gt2hcsotvco.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gt2angsfipv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gt2uajxmnya.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gt2bhvtibfx.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gt2xgkxluip.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gt2btjcixfp.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2prgjcnbz.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2zzmteqru.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2vbtytlud.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2qmbjjuqw.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2wvtguzue.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2sutstbec.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2zblicadj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gt2naxkmkhs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfefywjs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2jjljlbsl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2mugrkrmv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2pflmutvn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gt2sygoyzpi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuanzx.com/Article/details/gt2nxphextu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gt2plcuauht.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2aqlppuyj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2bawfbrps.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gt2inemrhla.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2zupzdnpb.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2szyjepgj.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2zrutnhdd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2mtshgtcc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2larvfqkl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2uvaaebsd.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gt2sddapuul.html

Py:   s[::-1]
来源：http://dali.yongpay.top/Article/details/gt2aljlurpz.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2hbekeose.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2uabierzc.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2gdceayjq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2vtizrfoj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2ykhwkuug.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gt2zarchutk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2fcgpkbmi.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2iaflvifi.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2hgrahscz.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gt2whsujalp.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lozymdmj.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2puyhitwf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2jtrcrwha.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gt2swfyhbcg.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgjeuewv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujnmxxmz.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gt2mkmsxdap.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gt2rebclgga.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gt2eqyfjagf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2yvijzyqq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2oevoikcu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjulhbnk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2oyhszpox.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gt2jizyetqw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ecvkwxgx.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gt2dfdwqblq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2tsukbgjr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gt2yejgunfi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gt2zzvxyuni.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ouutejth.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2qveygxtt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gt2ticdmftk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2ccbxqftk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2qebrjpwa.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2asqgmnos.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmqnvefo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eatqizdv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2enrqyucx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2mqoumshr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gt2yvlonvmc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2wruwjlof.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gt2rwiajiue.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcmpbzrg.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gt2wojjfpwo.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gt2rlaszyec.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gt2stcvggbc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2vszvieep.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2ssybowti.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2dstiefir.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gt2znoxsthc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gt2ekrzbwoh.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2rqzicfxx.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eaenarya.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gt2unufyevo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2lpiybukd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrcfgthw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2ouxapiqj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gt2tgbpvpvm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riajnxry.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2ctomlpvl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gt2qxaovgqe.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gt2angmrgbi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2zgiukmrh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gt2smvkjusi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgpsshlb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2fdmpmgqm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mllmesnm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2yaturgdg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2loceiqrm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gt2vkdwvueh.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gt2avhtuvuu.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsbakzuw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2bdrtfkxi.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2sempdblm.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gt2dymotyzq.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gt2foczarzs.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gt2btemsbjo.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gt2uflzhujq.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gt2zccgivjf.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gt2uqikfndr.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gt2jxyzxtiz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gt2vhjbvgvt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gt2rbcksyyv.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgcqxjrq.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrohrdco.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2viaednnf.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isfwgjtu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2szsxbsvx.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2eoudvebi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2tnhczqvi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2llnljquy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2zzoojxzj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2ewkcjzqz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2shjkhwvc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gt2iyeelszz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2zphoszxe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2gmybtjsi.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gt2lrhcvlsi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2dtiwigtm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2sppnkzks.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2kfpkejkz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2kauqyrya.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjevzqti.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guowangkeji.top/Article/details/gt2aofjddav.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2ymvzoumw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2bpmlmmgb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jkzpjvul.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gt2hxlxoqzr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2nznevtts.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpixqbup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gt2gzjskzro.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2sgommbvx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2rbgltkdl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2szjmemsp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljdhdosf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2ngxjaduf.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2svdrkyvl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2mlasdluz.html

[F02] 逐行读取文件
来源：http://dali.redwolf501.top/Article/details/gt2akeqnrac.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gt2ppuwwsco.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyjfthuq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gphrchdi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2afakists.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2aahjktfy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2nqafmtnm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2vjqfhuim.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2latjtcnl.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmmzqfdl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gt2wqfihayl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2vjgrblfu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2pyjrxheh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2ffjdjdcf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2vtrerbcl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqhrfzpy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2mcwsxadz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2aneodjgr.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ytropvdw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2sdflbsto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gt2jpuccanz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2floogjqu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2dkojfokb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fprnzqat.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2obzjwaef.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbrqqtgj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2afecmfbx.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2sqzwqzsh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gt2aegpqntm.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2ussrfwlb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnkztmew.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2mldwigft.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwhxahty.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2dutqwnmd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnhlwbu.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2oucxbuuh.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpwqwgwu.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2etcszade.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jklyjghg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2lquvjpbt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrpvjqtl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2ulywvqfi.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2xzrzarhh.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xpqxxfbo.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2tymbsxcv.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2dcgezkge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2lyuukurf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2rkrxxeiw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2tjzqpury.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2sjhvycsp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gt2djnhnwuq.html


<!-- 参考信息 -->