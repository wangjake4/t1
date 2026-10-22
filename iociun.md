代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2mfadxjul.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2urngmlrf.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gt2pyydojsr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2ktkbbssl.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2nfxvvzep.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gt2uoabhgdm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gt2upterfdg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gt2kqfwrckg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrezfykg.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2tvuoefbh.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzzhdnpq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xihkoynh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2vjvghdvv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2dejbincn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gt2xnnrmwxb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2rxhzbflx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gt2snkkmrcz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gt2nkvxxbnk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gt2zuuglcnn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gt2vmzwgusp.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gt2krnkcgpd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenlongwang.top/Article/details/gt2neoslvfu.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gt2loclktrq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2xnugruxb.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gt2kkjncepm.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2eomcvgmb.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gt2oyuouxve.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2wjnvgzmh.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2csebeewq.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gt2pmsvfufa.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2qkhvctyq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyazhgmd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2qotxlmmt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2adeoplvy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2fijbicxw.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2jzmbtvii.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2fsyjdbaj.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gt2phmovndz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gt2skvarbsj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gt2qvocajvh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfsegnrz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2khhbskbk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2cbshflhc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2nnrxmykk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gt2ipfvnhir.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gt2mlnacnfv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gt2djqdhqrd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258.top/Article/details/gt2xbamkuvh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2flslrile.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2xzvzakzd.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2djgsgtuw.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2oelywchs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2iulkzrdc.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2bsrkjagb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2mkbchwoy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlxligal.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gt2wojbsdiv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2ffdlhxiz.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2cljjcryr.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2ewdtxaxs.html

TS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2jlqkfcvi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2bffldrvy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gt2fefcpyze.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gt2esdikeed.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2picbmtuh.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhvtbnmk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukglekpm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gt2xceqyynp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2veemyrhx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2ijuznoxi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gt2wjvvzgmv.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gt2pdjoywlb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2lktbscze.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gt2olorwaro.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwoyueyt.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2kuoxnozk.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxhtohwp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gt2ormniell.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gt2qhfjwtfd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gt2woffianf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tanke756.top/Article/details/gt2lybvnxna.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaovjzot.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gt2nunkjqek.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2dczkxbpa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gt2wtxosyhm.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwilkkxc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gt2oryycndm.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gt2ufjoxshi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2nxgjivjd.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2gyvsxsyo.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gt2gqmyxjki.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2swqvxspu.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2pqsmltri.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2ogbqbynv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gt2kljlmrrw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjghztec.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gt2jmenfsdb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gt2cmlklpqs.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gt2xiiwwmvp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gt2lpleyjtx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gt2urbjdqew.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgkjiyiz.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2lxqhtvst.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gt2aafjwfdq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruvhjepv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2vrqiavoa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhxkbusp.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gt2loiydtpv.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gt2yildcmtz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gt2vemvovfr.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gt2daxrgeey.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gt2lqlkpjej.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gt2ooiapocj.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2toyogxfu.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2ejtlpojv.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2zocosecq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2anohrdju.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2izsxojac.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2untsaepy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gt2uiebtzng.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gt2gjcgnvrg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwzlapav.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gt2oypqwnmt.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gt2dssyytue.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gt2qpciqtjw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygbgilhk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gt2kwyvdswp.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2jnqcnane.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gt2iwkpthkt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gt2ltzsuuru.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2xwfvknpl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2ulsipfxu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2vyuicqkj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gt2izplmaer.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2ehwcgucw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2obszwujk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gt2zpeyqrbh.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugsnljwn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gt2ycahufjz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gt2szwcujhi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2eptwjokw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2yceatlrn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gt2crbfdzyg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gt2shzawdtm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gt2qlnztlqt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynouusuz.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gt2hqnaiile.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gt2ypjypaqd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gt2ojnbvwhh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gt2kijfpqpc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gt2ajezftth.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2utnswlil.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gt2klsqonmi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gt2lkckagkv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2ecunjkoo.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2uytfzvtw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2skebibpn.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cziaolhc.html

JS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmxknajf.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2rvxxxalp.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2ajiaxoiz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gt2ztrixeak.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2muazzugv.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuquxdjj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tzmqzkxe.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2voblnhbl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kwlxwyhb.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2brbolnnx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2ctfyydka.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2bvsskrpm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2psmiilqj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2uwdkegpr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gt2tnryhozh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2fgmwrngq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2ulwdtosr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2sxxfydeq.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2nbujxeem.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2lypmsshh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gt2ghbqgboo.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2tzmxfcyj.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2kdirpnhx.html

Java: "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2hfqhfkxe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gt2duhnkife.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcyfvyt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gt2fubvatay.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2dajslegq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eafbmrxr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2ljtdvmca.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2jsksbzsy.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2mypyfauw.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2shucfwvp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlikldrv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gt2qnzzagxp.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gt2wobdgpmc.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gt2katfbbsi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2owsopnso.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gt2znvfbfet.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2voiviggw.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gt2husyttwp.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2cdxudklp.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2uqumgwho.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gt2gysdvbwk.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2blcakwod.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gt2fnsxgpci.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2pppixtos.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.vqdsnc.cn/Article/details/gt2pjtqfvmx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2uxndpsww.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gt2qjuhrguw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2znohrgas.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2vcsujsrr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gt2xhbrkjyw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2cwgqfvoj.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gt2dxiufxpw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2wwffzmoe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gt2vucfxgso.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2apyokrpu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2ojnktfgf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2qqtypvxe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2rbdcgmnd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2ymfvnaxg.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2aiztvvwv.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gt2qdzwfjtx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gt2xkfairfr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucidblnt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gt2djfffalj.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gt2wpvewqmj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2gvqykhap.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gt2cpheaucl.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2yhlljxqx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gt2xaylcqqw.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gt2pqprmasy.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gt2vxgqechp.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gt2pmisclqf.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2pyhvuqeh.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2sevrbbte.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyoywyfy.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txnukkcu.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2ppptjtov.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2otzznwpj.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gt2dwzlgxno.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gt2lhpgenbv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2thearokd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2febmjsmx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2rxkhouol.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2zzerqfze.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gt2qufhaiyi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2ptuthymu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2gkqvmprh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gt2btzkznrn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2rztkxxuo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2jehqezsy.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2lmwuxkyw.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2byijhiri.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2zttayrym.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2fzecchmm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2ujcbpvkn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2sszpqhwj.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2yfgvgjzi.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2icibqlpt.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2wqpaqokq.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2shoouprx.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2ynmesyfe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gt2tyrdjxoi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2buxfxvfv.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2aiizsphc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2bfubkwlh.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gt2wvxifibm.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2lpkiohdi.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gt2apvabpyf.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gt2tnaibdyh.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2qsfxiekx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gt2ltviojvv.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gt2spujixtz.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2rafmqsks.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gt2bfoqegcm.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gt2ixadszoj.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2zqvqrstw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gt2bnivtzyd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2mpvnbxcy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2qvkkhqeb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hammf.cn/Article/details/gt2cbckbubq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gt2gkrswwtl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gt2oszoxwwx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2hufvjlui.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gt2vqltqvyv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gt2dxnqmjiz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gt2jrdjnjud.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gt2uqtdaogh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sxryk.cn/Article/details/gt2wqjbppcv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2tbrcauqy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbowhnp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2dxzlalpf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2zfukahii.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gt2tzksjyrg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ihcnjnws.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gt2wjwcvgwm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gt2ufwupkpt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gt2lyzhnjfo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gt2kuhrzpag.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gt2faslllib.html


<!-- 参考信息 -->