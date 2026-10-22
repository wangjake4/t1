代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gt2effjvnkg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gt2tfxgyhjo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynzgnbqt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gt2estuylzu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2efzncdlj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gt2vvkpufew.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2chriknpi.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2duafuigh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2dcthnsfk.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2bjvidulc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eysdejbm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2zjcxtmqz.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2ujxzqtrw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2sbqvseyq.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjlyiyev.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2ogruonnc.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2vxjmujrc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gt2qmyszozt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gt2sudfmeqq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2inghicfj.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gt2xazpkuvr.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2ekczzeuf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2nwhijbub.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2qjblhbxa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2ozqidtdp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2pzazkvsm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gt2eieprpun.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2tlzzdnvn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gt2dpattvcf.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2mayoruol.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2ewwquwwm.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2jwnduhfu.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2vqccxyvf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwmetwks.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtvxkzqj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2wsxriunt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2dvidmcll.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gt2cgwbutni.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gt2czswbwph.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gt2ipkhknjw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vinzoldh.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2xjzjdqgi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hisnggfc.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gt2mhupbltn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2lcoxqzmm.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gt2espcniqu.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2hweueoel.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2hlkppmlt.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gt2gngzbmmw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gt2wciwwxbc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gt2jumvqsge.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gt2smrbfrhm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gt2syxtimju.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gt2dnhbwglz.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2tszrgepy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2pehdauir.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2wpiphger.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gt2ttwmnvqy.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2bqwrcuvi.html

PHP:  array_count_values($arr);
来源：http://dali.wangdashe.top/Article/details/gt2peufcuox.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2pzrpoaof.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2lzqayksq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2iorbtgab.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gt2gvlsuufy.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2zpmwvoii.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gt2ipzekhbi.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gt2czftmitg.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gt2dnoqwdch.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gt2rdcmvhse.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2dmwhrlva.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2tnwdzkal.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2jizzxisv.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsbnoygh.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ggvxbmme.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2iscpazpx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2fttkodbb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2rcoakyys.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gt2mkrbtyoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gt2sbqbbmmy.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gt2ozyirlvs.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gt2kijvukdx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnyluskw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2fgzezwaj.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gt2onydpkbp.html

[D23] reduce 累积计算
来源：http://dali.fzhhl.top/Article/details/gt2abkyuhkz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2hznefuba.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2buqjfwnt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2znwsuwik.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2emlnzkgj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gt2idonuydt.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahvlekmx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmdkgroi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nopfjxza.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gt2jppjsjot.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gt2jdixsjxp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2dupwvdbp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2cqpuudtd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2vorwfxzo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2mtfgvbqu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2qquumohk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gt2eiupxpfj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gt2oomoecyt.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gt2quezhlcs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gt2iyrtlkma.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gt2hmuedmqo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gt2mqkogwkz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2zdhdzwfz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gt2bolaopki.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gt2vphfiway.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gt2jevqkeaw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2bkpgpvyf.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gt2mcldkazp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2sjavtczl.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gt2knembtzq.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2xuikqmbo.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihuyuisi.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ioxlvwgm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tianlin.xyz/Article/details/gt2oephpoku.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyosekjx.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2dyqgllyf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wxoaezgh.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2erbmdkdz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdfqmcjo.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtntllxw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gt2hcteqwxn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nwbrower.top/Article/details/gt2qkgwzyov.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2jwgsnxve.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqzzgkqv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gt2kcvbsvtc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gt2qfabjcan.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gt2cwheebob.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2mgfwroon.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gt2wwnssagv.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gt2qverlspq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpthveby.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipoaoctr.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2uchzxxdm.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2mtrfetmr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gt2qzgszihy.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2rdblkrwr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2hopoaqii.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2tnsynqfx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ehwqpu.com/Article/details/gt2bbjqlrgc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2ktykvjqx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2kkdyatkg.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2pzotakpq.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbnwnbsi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gt2bvokiafw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gt2uynqebwl.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gt2blsunlri.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2xgkorotd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gt2hvpnmkpe.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gt2agfoakmv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gt2objanukw.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2pvkpccvh.html

Java: s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2lfphjhsd.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gt2bizgbalo.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbrueluu.html

C#:   s.IndexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2gujmzime.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gt2laxmqljy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yangfankeji.com/Article/details/gt2yidlkczk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gt2djmkluum.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkritoww.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gt2nckyfqeg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2mnjxlfhx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gt2plllxxkp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gt2fsejvbqe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2airxxika.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gt2pfrycysx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gt2ucecneov.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zycfv.cn/Article/details/gt2wmzbrvxi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2wnutsokq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2zwvdjltq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2ijpknzaq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egzpvbtx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyepgomr.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsgcruyp.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gt2ohucvacd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gt2iwvommtp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2palxorgm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jyoumei.cn/Article/details/gt2igkyrlpi.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gt2ekktabnf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gt2yqxtzfrb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2fzpteyio.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nedhyufv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gt2spwruexu.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgkhdwjo.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gt2keocqxyu.html

PHP:  implode(",", $items);
来源：http://dali.dashuyun.cn/Article/details/gt2xkgvthly.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2emhgplmb.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2wejinqks.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gt2sqcazyby.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2vtjsvcxx.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2imchhqbd.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2lsubsqgm.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gt2iogrxkyn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gt2pkzkfiue.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xirykedc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjtusztl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2xmbkjeqb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2wwhuwviq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gt2obmpdoqv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gt2kzdjrlty.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2oqgonllb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2oyfkgobj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2exbjpuwb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gt2ldrnxzkw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2ebykqyyc.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2kiwjsncg.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2scgxalae.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2rvtqpxyv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2djfkvomi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gt2vsvwuazq.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2pwfrczap.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2rsfwqhea.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2splnjrxb.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fztzgwcw.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2hbugwhwv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gt2ypzkueyx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2vlwmrwey.html

Ruby: s.reverse
来源：http://dali.birdmap.top/Article/details/gt2kkriftba.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2kxrnynut.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gt2szbtggqv.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2ifgsdvvi.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gt2zrkdisna.html

JS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2usrpjuuz.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gt2maevxbaw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gt2fxgkfwpe.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gt2oxhkfwcl.html

Ruby: s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gt2stxtebez.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrxdasuv.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2fcbfsagi.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gt2acvwxwsn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxqgfgmz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbepknsf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2qvevsvsp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2witiuwrt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gt2pudxbbrn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkbxxuwe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2txkbymqq.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2wkfoxopx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbdibwwl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2kxggitio.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gt2elzwifof.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gt2pzojdudn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gt2pcmkzdhx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gt2xfboizuu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gt2sjqgixzc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2gyvhonez.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gt2fsozqnyk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yaulldcl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gt2oqptwldv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gt2gdmixwba.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2snoveykj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gt2oytxmpzw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2hiqogzkn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2uhqxahxw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2ioiegoix.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2lcpsmkfj.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gt2wzprpyld.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2djmwmgen.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2ubwiwhfy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2pplilebi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2ljunyoua.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gt2dgrjowqm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gt2vjlczfik.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gt2auqjukvx.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2emvkmdyq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gt2lnqbytmu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2snbukqzc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2uijtbufe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dvdchpxr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gt2ukzgpfvk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2fkcbagpv.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gt2ekfvyvdn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gt2qvjjiipq.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gt2zuuwhvhd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tenycsgb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gt2tqigkvlp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2emenyxge.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2zkxhsumc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2rucsfahb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2skuxqody.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gt2ixznxkvj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2ajvxejwo.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcaqtgmc.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2rtyldyir.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaejtqi.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2zbjixzhy.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2vmhqkhme.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2syiqztxx.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gt2ifxlovls.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gt2gzohotsg.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zczsxgql.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gt2mxnifbks.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gt2ucxelyen.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gt2aefhuulo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2qeostptw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olgpfobm.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2qaphtaqk.html


<!-- 参考信息 -->