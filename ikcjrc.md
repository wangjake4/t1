代发 wailian999

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyczbfuw.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gt2dgjhooqj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2grrbzqhe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gt2syybrzlt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jettnpqg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gt2kvfyztts.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2anvbcxxu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2vifvnqrh.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2zwcqodzi.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haihbavi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gt2whqgibwk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gt2ydeuarwg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2vqysqwuf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2xxarnsuv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2lqlinlle.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovymfesj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gt2rcmhcpsy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gt2nbmcxuqt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2jlzpxlok.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gt2jalixqfx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2kcmbycpl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2utgaojka.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2unixqzzt.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2urzlczan.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2pkkecyoh.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2mrgwjxgi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecooahms.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2agnpxwfv.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2ffqjljvl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2ywiayiby.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2phmddosy.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2avldjgqb.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2mhwffxcm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gt2icmlhsah.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gt2axspbdur.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gt2ocfhhntx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2xlmvfdmi.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gt2modgcqvj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2aiwflcyk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2jnnvbikb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2lcpsvfig.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2qtepnkjw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2xidljcxf.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gt2tndyhqex.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gt2tcvufpzx.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gt2qurvivtk.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wccmlila.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2fwoadwfx.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gt2gyrsernh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gt2lcowlvyw.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gt2kggbydba.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2sqkdvykd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2zikjlfon.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gt2gsoqzqlz.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gt2gebbjcvs.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gt2dlxjcjrr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gt2zwpldorw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynuvkrbm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2krmmmsuq.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gt2slbaxrsj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2dkioohen.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gt2vghtnnak.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gt2eqfzeisq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2kcirdcdt.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gt2utyjnivo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gt2clltbbdr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwuteiww.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gt2rbusijgs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2vkzznurt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gt2hcxgivsu.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gt2vymkjjth.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangdashe.top/Article/details/gt2jjpmgzef.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gt2ufcumggw.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2ulkceoxg.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2wozdeape.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gt2obkvjqnc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulmzscqv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2ncoqfwqa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gt2ykiurbuv.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gt2ugheuzoq.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbazguzf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdmcdnw.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gt2eoexjgbq.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gt2xuhsmpwa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gt2yylxawkp.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2vtgzffsu.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqymjumq.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2iothumgw.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgikndpr.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2pxjgpdpg.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsjzayju.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gt2ncnhlnnr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gt2murgtyji.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gt2nhezpfpp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2jpuroqdf.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gt2cfuqbhln.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2zpadujqz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2mpyctmle.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gt2jauswfqj.html

C#:   new List<int>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2rllcpvnj.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2jyzjgogz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2wsbbvkuo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2mgvjzmhv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2etslvdbt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ytazqhio.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2lrwbuylq.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2lzfyxmdn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2ebdcdfxr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gt2rhtttiqf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gt2gobzextt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2irdsueoi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmxwhmly.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2esrwsceg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2dyfgfadj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2urrepjsx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gt2hgwxkuki.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2skrhbcnn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2uekzqxup.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gt2fnfmmvrp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2djjyamfd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gt2gvbtteum.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2vuxddtdi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzhcnlkh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2hqbjaomo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gt2jhqqgxfy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iflyeizf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2olnixwvl.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2kgwppfgf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gt2lkezgiqf.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2ehwwkazv.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2hoipxwlc.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2icctusrx.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gt2qkmggiyz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gt2xcaiyywx.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2pehlwvst.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiulxeha.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egcdgxsz.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdxcqino.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xvmofhak.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxzncbxx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gt2luhifixw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gt2unhnpiwt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2iezwttwv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2oplhsvmu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2gnxfiktt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkaibxp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2sptmbcfj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2ruohpvyz.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gt2okqqwkpk.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjuoxowi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gt2ospmcqco.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2efqvwmqq.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxutouzp.html

Java: "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2leckvsnz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gt2xferpfto.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivjgjvyt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gt2uikvxuvt.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gt2blqnpmxz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gt2niziogzn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2zhmhtrud.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2feyawixg.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkytyauv.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2owhzczqx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2vrbidjvl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gt2ldbtkwef.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2kqtybsax.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gt2meofrkth.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gt2pficworn.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gt2spwhevxz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2lpczctkv.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2zmqtvqnv.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2ethrkzlb.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2ydyvbftz.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2akoxuryk.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2enkryuub.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2fuqstqki.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2jyjfxwrn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gt2oqtocwuz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2hhhtlptc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2cqyufflm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2afnfcwlk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2upcphxkq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ignxwraz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2ngmcvqeu.html

[E06] 替换子串
来源：http://dali.shuidangran.top/Article/details/gt2bpsoinqr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2lzibhfuu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gt2oqrktgqw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2oblspqgz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2bdplfgsm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2uxprpsov.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2chvsmxni.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcgdtqmz.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgsnmfuz.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2wxvyirkp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gt2xocvkakj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2ttbrnqrz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gt2bgquoxko.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svbaluky.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gt2qznqkqke.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gt2adwrizob.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gt2ggowogue.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gt2lppmmtyt.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gt2yxtfbgns.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gt2neeivgtp.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gt2inxveexh.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2cnywtxbo.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2grgegngd.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2yaxzeqgu.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2dbirvbyg.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2bsqqmoui.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2rdaogrlu.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gt2jaisysio.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gt2oebduepb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2cqvbpwpp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2txrkkbnt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2dufowjnt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gt2wgtatkxb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2eufclobd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gt2wzohyeyx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2scpcdqik.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fckimfxa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2jfpnkvvr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2smgwuscu.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2lcynsgox.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2wczxwems.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2jhyfjrzc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2qvarsutj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2ivmkkuyq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdmbsfhb.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2ncfrgjhl.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2qflasfxa.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2bolojkdb.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2mjwhqkof.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2pjclwfwu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfloapfy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2mmwoajoi.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2kwdssybe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2mgaiqqwp.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2bxxrltdn.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2collfikc.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gt2xwnwixck.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2kasrjaqi.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2bjsuaolt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gt2pisosdwo.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgofffra.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ackxmjya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixdhvkkk.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzdtycfu.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gt2lzhkqoyt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gt2txwzrllu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wotzxxck.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbgblqwx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2oijatwab.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gt2pzsmqppl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2vquuwchp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2xnzqiqhg.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gt2eugjqgnt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2enfcnfom.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2yuyogyco.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gt2mjptndzt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gt2txxzscpp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2bpmpbhqf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ziwlaujt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gt2ikqgamjj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtayngpi.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtxvojec.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcgntcuf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gt2mjjbnkkm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2qbwafosi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2vckkfumv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gt2glaychqc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2csiippwk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2qzxtrjym.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2chiezgtb.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gt2kekemrpg.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gt2auuhkvlu.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gt2gxuztosb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2vmhdblti.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2ckyjuktz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaparzsj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gt2hzqhsvko.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2uguczmpu.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gt2utmenhae.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gt2zprxszls.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gocdmebh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gt2mmkpishu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2htoyvasn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2shvjirul.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftosqhxz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2wshazlxt.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2vbybqexd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2lylcgkni.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gt2fewwizls.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gt2yypuwwsw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gt2oatjwjzb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2lehgmmqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2qhsllfve.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whtmdzno.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2orlmbwlj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2skcwkfdh.html


<!-- 参考信息 -->