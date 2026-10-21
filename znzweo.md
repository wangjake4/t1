代发 wailian999

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtokswuatm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtuvexaues.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gtvugfvotd.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtqlcrwuqn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gthloptjpr.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtgjtxyizv.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtzrgqlhaz.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmfbkgvx.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtmaerkkwh.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtsnxxngzo.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtshtyzxpw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gtikvgsmey.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtdtvgcufl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtgmrgmcac.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtgencklfl.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtqzskdpyh.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtsnnetlva.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtsxjzmvch.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gttkmhfmlm.html

C#:   new List<int>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtdprgvsoy.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtomkapyvq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gturldnten.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtzhlzmtsx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtkfhxpvqx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdzjzztkr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtfvjmalfj.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtytsywxhq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gtrchqhmsk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtljefansj.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtuvsgsrzb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykqkgznp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gttqznfbqv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtlnwtjcpe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtpcjtcunr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkegisfp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gtbrvwvoqf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gtopeknuea.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtkfstcrfz.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzifxvbh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtbfrjktut.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gtsdsnnaoe.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gtsudezrbv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtzflfjaeo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtfmuebmcv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtfduymdju.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtlvnmxkwp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gttanujqww.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtbcdrhiul.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtdqbjxygs.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtkycmkefm.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtiwpafvds.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtnggxmqtj.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtoqodyiwp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtsenzncmc.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtvnwfooyy.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtmuqfmkgy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqcrucjfz.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtidlerlol.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrivooymd.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtzycuenmq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gthrcbpiyn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gthsbpansy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtwcdzooge.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtftkugyyp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtfxczqaka.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gturxwloki.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtamuzanqs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxnorlro.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtiplqpmnh.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtkhykcstj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtztefihvs.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtwwomlygt.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtqaynsvym.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtxnvowjsa.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtrcbvunui.html

Ruby: "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtoainseri.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtrvnywjlt.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtowscqvid.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtsstkinpo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtrarszqgj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtnvyfwydf.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtjygggsre.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtvorwmtaq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtoctyapjr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gtetodghal.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtrbqdqctq.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtfrixzzpo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtdusipmwz.html

PHP:  strpos($s, "x");
来源：http://dali.nanxuanxn.top/Article/details/gtmyzkxfwe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gtkimxkbup.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtjfebirmc.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtkljmkswg.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtxiaticcy.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtmzthwguq.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtdcocwffp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gtiagsdibk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gtnchwcdbl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtojngqdew.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtvelotkcu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtqbogwtxi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtvgputagj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtpxibcxvw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gthcqqynrc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtogybowfc.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtypgceera.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtautdpbme.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtavekeveo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtvvhwskny.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtxaicmret.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gthaqytbcc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtminuxvmq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtflolzrkk.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtbupasxlb.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtcgtmsgzc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gtgsnfxnob.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtlrrpifmp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtlocqtitl.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gthpdulzhj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtpycmlfum.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtljmldghy.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gtemcbxcqj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtmzuuylpy.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtvtymlkpj.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtbiajouga.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gtrmmjtdwu.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtcnmbzsnk.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gthwizibzi.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtbkgnfpfz.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gtezrvnxvh.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtdgthpivz.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtalsbxatg.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqsdahtr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaqxqtmo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtgeqayqor.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtiuazrcbo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtrnhgpodt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtscnalluf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gthqttpiea.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gthpddzbto.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtoxbilake.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gtwuycadyr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtimfvuhcy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtjradfmwa.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gthwqtfcwz.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtxtsydnrt.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtydgmoytm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtnppzdpsb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtggpqiubo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gtdgdqfqnw.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gtpgortmsj.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtasdxctyo.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtfdqboflk.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzavjgaf.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtyxaqgmaq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gthekddkfn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtcxdeshea.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpsxxsgl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtwsvuelsw.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtlqotisad.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtfrcvqzok.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtgixtsrsb.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkcovoon.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtcnfnqgqr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtklrlvkbz.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtwgjrzsvb.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtbqobixjt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gthuujmrss.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gtofvkrllg.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtswuxmdlo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtimzmukks.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtysecdtso.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtumadpqze.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtxwudlmwo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtpgdkgeeb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtnzktdpgm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtotvxwojp.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gtddynrjyb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtqzewcjqt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtnjwmqwdr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gttscsuedt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtbclmozvb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtyijczoko.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gtzuanzhvp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtmppwzpyf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gtseztworo.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gthmjvmrau.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtccdfiagy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtgejaztge.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtrktwhptf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtkwcaxsaj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtfouubhvn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtygcnzxie.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxiuppiqj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtttwczwxc.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtlqkwdnak.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzstiliwd.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoebwmrcj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtsrfukfvi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtlndovkzs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtdxwsziny.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtajusltfk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtumnwehvd.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtrjnjjcgw.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniuemfmz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtgureelyu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gtapuawobv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtlsdorcto.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtrxzfporz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxlcqcnu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtqqzojwhw.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtjlfcuouw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenzqeyjr.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gtyzateoyn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtpolwcxkz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gtgikocqra.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gttqrcxfre.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gteomvinzd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtpdnacyed.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtndzlypbd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtewwpgchz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtlekdujnz.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtoaewxtby.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtkzzhlxxr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtgahdqfsh.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtjmodflun.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtmzwocdqi.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtmnzdlujq.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtrkjvibiq.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gtcmwiuuxl.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuwqhcvm.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzbpkumo.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtdcikeoax.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtzkcfoymg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtbtgqybmj.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gtftewpuoj.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtpdmqiiag.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtjubolcyd.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtesrpgtve.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtayuvqqzd.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gtzsngbvft.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtapvkybaj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtntqsykql.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gthbezdbwc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtwcklznnd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtqreyuuwi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtbshohdkx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtvcpxbkig.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtssgzaztf.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gtzdyzxhbr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmclpohjt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtrqyykkaf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtcrnnhayu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtiptqarmn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtogmguurc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtolyvrush.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtebxknber.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtobitjsgz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfsubqcxy.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gteldwyjif.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjqmqughs.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtenxhxxri.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gtpzxyudtr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gteqcvyjgb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtabwfdnhn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtqdyfcxor.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtzujaaclu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtekfcuqcw.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhqixcek.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtytibuggy.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtsysguyim.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtsourxmmq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtekazpqma.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtkqigkrih.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtxxkkrrks.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtuekrrbth.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtssomjjhl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtqdjpjrzk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywztwhbm.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtccmeqfku.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtjkhlgwix.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtofppsbhk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtsdozcxma.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraxfwowa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtzjismpaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtdbgexqtv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtsrszehel.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtuhptsclf.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtqgqezfne.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtujrayxey.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtrfcjuxze.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtagngenbs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtwgxtxtlm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtrrdbrfud.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtstywbtwf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtursplaxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtgdbgpbgt.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtadocyugm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtuayibyiq.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtgubtxsgi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtyvyakznb.html


<!-- 参考信息 -->