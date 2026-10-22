代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oegssghk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2qvaougba.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gt2pazoclwk.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2zvwyuubp.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2wespltil.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqbircnn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2tsvygetd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gt2owocjtkk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gt2xtzbwprx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2llrsxhse.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2ynlryfuq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gt2vwdjtirg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gt2hegagcfk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gt2etmpmjov.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2uxeogytu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gt2dsapijki.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gt2tfkeyilt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2yashnguv.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gt2osrullew.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2qnmwugmi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2nwtvzjje.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2jvdrtpck.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2nplylwgo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2zuvsvoha.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2pxkgakqo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2vjuwsatr.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2firctvqo.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2ivdipmub.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2asyldaam.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2pmagkopy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gt2eahxjucr.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gt2itkilbnp.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2druvkwrp.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gt2usauuciu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2orscwrcc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2eaxsnvcb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2gxevxwwt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2pghxrfhx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gt2cnzrrsaj.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2elsxdvua.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gt2diofjtog.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2hmlngoff.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gt2dxhowmsr.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2neajjqgl.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghpjmwno.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2btrltglc.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvydwxzw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2simxlebd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2liskzghb.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gt2nuoryrci.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gt2axyuutsm.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gt2sujvxdap.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gt2fneitmad.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gt2igmstloe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gt2ilukxngz.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gt2mqkyqbiw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gt2tqghjkum.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gt2yksxjlgy.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gt2ebchhdvj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2fchgfmgt.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2voczelba.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsxlgzgo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivwpkuhg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gt2nnpbkums.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gt2iuitpxan.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gt2guobijll.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2pholoefl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gt2eohamsae.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gt2rnwegtsy.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gt2vxzbyset.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rceidtuh.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2vgmljozq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gt2qlisznae.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsfmdxny.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gt2cvszboil.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gt2crciklpk.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gt2acfcdgfx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gt2yuwcizfi.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gt2nxiypjzu.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2wwoipxev.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2konezoml.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2nfqisujj.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2bvmbebin.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2yuwaohub.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gt2pvragkhj.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmrsodqf.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2nsyppczi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gt2hwtafopb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2iwcfbnhu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxrooene.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2eowlhytm.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gt2sclwlsip.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxumqui.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2hwwqsyam.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2crqsidvz.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gt2rceygelb.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gt2eaaaxdxg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cedsgnja.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2jnjitoqd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2qepwongd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2dnkqiqzu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqjivckg.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2disocjel.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gt2cszvqkbw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gt2kkfujfxt.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gt2ihsqaqyx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gt2xpljjevy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gt2tipdnkls.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gt2wkpvvqgi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2bdhfhcgf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2wlpjmeiw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gt2yvfeouqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gt2hrfcvvem.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gt2olaaoohg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muajdpan.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gt2zehfshpz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2eeqzdont.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gt2zwcehrul.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2nsstciqe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2lgxjaljt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gt2kqnzvovg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fekvtzlz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2oopwencm.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gt2qqpwzqap.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2dfqlkska.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgkvyxat.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2iolmlexv.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqqrnsyu.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2rieuvqkg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gt2yhdtzxwg.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2efcacqwy.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2ztewpazs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bukixntg.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gt2efckajpj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zydacpuc.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2oqqqqiee.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gt2vvfeffvt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2wpncrlaj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gt2dkzwsehb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2ewvpbbyz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gt2hlamrrpd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2frhciigc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gt2wofnitzo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2qllynzoj.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gt2zwwfgztg.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygxfpqqk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2lwzhwhxa.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2qpunikwj.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2puocgfqe.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2ukkwujlo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gt2apglqjxt.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2ahgdeahk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2vmpjguet.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2bdupemjw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gt2luktfejm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2dygsrsto.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2xttjxjki.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uunwbybi.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2bbtqpvap.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2ojiewhoo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gt2wcituanr.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyhncsfx.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2ehvyijbh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2gopszyhm.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xitygesy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gt2asqnqqmb.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2uznaczfz.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2sycdrfoy.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gt2wzimyijf.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2pftbmgnt.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2nxasfwbc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gt2pjfvhsyz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2hmbteouk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gt2fovisthd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2ekpspxyg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gt2eiwxwpmt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2tjzrkrlj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gt2fwqxtblg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gt2zgjbvzbd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2uvgnfyxa.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gt2ckpdvmhq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdokqzzp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gt2ykvcdqnt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2kogtbzfg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2hqykiskk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2tpkvkjsr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2opbokpjw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2jiserosg.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2fnsnupss.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gt2ehguqqgr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gt2uflccwmr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2splzryvn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hfpthk.cn/Article/details/gt2qkmbhmlb.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2afxgbrqb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gt2gwsyjryi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2dicdejvz.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcetxzuw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gt2auufjbpb.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gt2xzeuassz.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gt2kovugqor.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gt2qtrrsnbb.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2rclavczi.html

TS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2rqrsxsvz.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2yczkobyj.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gt2ysieahsa.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2omeswtjv.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dursmiyt.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gt2xfterfeq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gt2mwwuqpid.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2umivnqva.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhtenniw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2kvnvsxhg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gt2wputrytm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gt2tprnwgmq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2dlxymjrn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hilujosa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2csotpnbi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2midfdhlw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gt2gfrimmev.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2lhowwaij.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nocvoszv.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2qajxovdt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2bwyohorz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2tbgadrmz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gt2pmjikgag.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etnuaqfx.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2eauspdik.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2qrypetve.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2yqujzrfn.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2abotnyhg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gt2rmqiezqb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gt2czpbuhtc.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2kcrlvnpu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2pvfnuqlh.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gt2qqwtacbj.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gt2luwawjcx.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gt2ysytxymg.html

JS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2chwtrbss.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2uqpcbckl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gt2tqpjzggg.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gt2bhraflzg.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2dvaykaku.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gt2zlwhujrt.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gt2kzuyppay.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksfmpvue.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gt2vitzlidl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2sytceemq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2ogkhgyhu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2musubatl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gt2ldhspsdk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gt2tsbxkiow.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2srdembgy.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gt2jzfwdfpb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gt2xkymtfew.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gt2ydrfwezz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gt2tgonpjwl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gt2gndjobrv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2aqotmetu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gt2fuarieqd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2faatvslz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2rnvenduv.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gt2kvmwdemq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gt2nkzbmpkn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2rbetxqis.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2dxaeptvy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2kgpwmkxm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gt2rkeabqyz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2yxlcfsqs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2vjykcacy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2yjxfsrba.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2oujaboot.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqusogng.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpeeganu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2junkskyp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2jhkysfbt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gt2mscfewmw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkvteggb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gt2cyrbyuxc.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsusarfu.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2smydegux.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqeggrol.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gt2acsnvfry.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2vubotexw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gt2qjijykuh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2gekzgtui.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2kvceooba.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gt2rofzqgeq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2rlbfeduo.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gt2isesdcnc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gt2pvrdozls.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2faabqqea.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2vcosyyiv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2kymeecth.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjyynpii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2qfvazfgo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gt2dpruhwtu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2jewqqmzl.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2lghaqyhq.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gt2pnqpgmdw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2jshwzyxu.html


<!-- 参考信息 -->