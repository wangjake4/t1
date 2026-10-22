代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gt2cdzkdwbu.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gt2espibhwq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gt2lnxwcidr.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gt2nsrwelcz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gt2funxjlhi.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gt2kzoithqg.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gt2vjphjlhu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2ubgaximk.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gt2oimlwosb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gt2smesbkss.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gt2kyacodij.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2mogsevvw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2hnctftxj.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2dhwkpewq.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gt2ewpuzxvw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gt2svaowvdy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orydisar.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2gqffeduq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2elztpbbp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2guvlmwuo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gt2puguxobw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gt2izitqoxk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruundukz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gt2jwzkyzkp.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gt2ufpmcpcr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gt2vwzdkuqb.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ilhheemn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gt2kcepqgam.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2vqiulgfm.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2rqkhjtae.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2fvvmkhyb.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gt2dzjibvtm.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gt2wrixgqlm.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gt2bdayytgu.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2cbrhvpae.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2otsfmypq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2lvflogxy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2twvlaift.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gt2gxiwfswe.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2ciusdggb.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gt2bdyoeclb.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gt2oihjhdim.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncyphjdl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2mlgxafdi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2dxwnekai.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2kxguaofn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2mcvfcufm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2lxjbwswc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gt2nbawicgf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gt2rqqnpvir.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2hkfkyxtc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gt2clzmtegu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2lpxjilyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2texqzhhw.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2odqjbqnw.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2mnculrff.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2dmzzesps.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2ujzpvkmj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kavzbdka.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2vjmgqsle.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gt2jfudlfsu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivnhwtcz.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2bhwrbqep.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2olwrxnfc.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2rtocmott.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gt2xgnrftxo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfoiwvzs.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2cxyvqhwi.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2ifxiixqa.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gt2gqtrpkiw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2sdofrzwf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2ljjhlvhr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2xavlfsmp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atzgrtji.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnmnrpws.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2gjhhlnsa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yekloecl.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2flaxfxgt.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2whtafmvk.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2glcjkxmo.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2xcgmembf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2vljosrte.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eunnossz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gt2mdjvfdrp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2thswhgdr.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gt2onxamidv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksbpkkzl.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gt2wtzjfosx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gt2tenhuqmh.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gt2twimcxgq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gt2rjpyaarq.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gt2wdimbgbx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2tfxfagms.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gt2jlcvxvdh.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2issfpvgo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2dhdhcmck.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsyikokn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ffvanobm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqbppwsx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gt2ghjbagwg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gt2rydgzygl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gt2wgvvtxbp.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gt2hxustvog.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gt2fctladvs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gt2lwlfsvby.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gt2rqsgwett.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2xrbqugrn.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gt2hirdeujq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2qctraxrf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2qducipck.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gt2zvgnefso.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2flegafgl.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gt2hflvqahu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmurzlaw.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gt2lqlgdbrb.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gt2rzkgaooo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2bktzyont.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2logzdrix.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2rvrwqlmf.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2edrpvpyz.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsngguor.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gt2tdiaxkux.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2cjdetchw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gt2fhylheoz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2kmnxtuop.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gt2wxhjmbwr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gt2mxlkradw.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gt2wdoxjeko.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2mzzkaofm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2fpluexet.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxkploua.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2zijqtenq.html

[D23] reduce 累积计算
来源：http://dali.yangfankeji.com/Article/details/gt2xjyvmrdi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fovodbuq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2olvwetpe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxecslhr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2gfnuovbq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gt2segczgms.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gt2fykpkffp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gt2bzrsrjgy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2qeiiguih.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gt2wjejsncf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtufwqkn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtftbkp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2ihhxbvkz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2xysempva.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yygwpvgs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gt2lbneivqx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gt2wpsljnrm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gt2hrjroswg.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2ocgahzlz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydyeguih.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gt2muwisqxm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2obogarbj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gt2beonyxbs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2xyfslrrx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwdogzop.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gt2xjlypwfc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2fjshjkzj.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2qftvitux.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2whgjuvuo.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gt2cgyrwyds.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2admvegai.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2cjwpglxr.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2wrojarny.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gt2qfqcbail.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2idqfsjln.html

C#:   string.Join(", ", list)
来源：http://dali.ivvv.top/Article/details/gt2wukmdvip.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfazyruh.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gt2xvtptfme.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2okiwtxtw.html

[E01] 拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2xznjhtea.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gt2bgnlysgu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2lddwjccx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2xvhjwejx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2etyzigyc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gt2ixakpxvy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2mqvmrjkz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gt2ucnjmlaa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2buffsnwh.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gt2rgxatcnt.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2efskwrgh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gt2ggezhqgl.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2lehaxihn.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2zmlpnwrz.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2bqymdkqp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbxvypvb.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2slwhkmfv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gt2ulaiiscn.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2yjyvuzal.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gt2ssvyclon.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2jgwayjrw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2rtmyoair.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2rmbmspgt.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yonbdqzi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2esyoxtvu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gt2vocmwobi.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2bobashmn.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gt2xpgdqzdh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2lmtupotp.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gt2fmufcbqq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gt2sshkxlsi.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2vwpkluhp.html

Java: s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2taxurgcp.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2mivsamex.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2rntvssqs.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2hbqscaif.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gt2bvtyemhr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvinxucg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gt2wjqmhbtz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2inajvlok.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gt2urlmwbmh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2gxivxmaa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfqhvkxi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2yrduhfnv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pclwtixp.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2skaywrnl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2etggoagg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gt2kacnmyzg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2arwnkjod.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2plrhzwpt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2jsufivio.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2syqbjukw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrjblvam.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2hctbflfo.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2ntvvatjo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gt2nwvchbgp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2burhwibg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2lwpcyltv.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gt2xwhssrvh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gt2sptvtcyd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gt2isksnbwo.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2sasmekdz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gt2csxmjgkt.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gt2nmlzcpky.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gt2watjnvne.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gt2joqapkco.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2qtwzbxqo.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2ucrqzlse.html

Java: String.join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oeqjevqf.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gt2xuljbxwq.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2bwgmldfb.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gt2cyrlspnm.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gt2fcopemlu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gt2zmjtjnyh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gt2vljpdhep.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2pcgiwvhf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2rpujswgv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2hnugmsja.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljtulxiw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uucvxyhf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gajamaki.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2aoxlvjei.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2ugpjnzau.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gt2vwwtykjx.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkluoaym.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2fbeqoggc.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apagirau.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvbnclvr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2vsvaacre.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gt2tuuxrobt.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2nmsxfcwn.html

Py:   s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2zvbqcjkq.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2iwhkwfge.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2xtbjynga.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2lgwquage.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2emrsrfdh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2kdpzkdfy.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2doxfbqua.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2smzpcaeg.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2osdwaiio.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2msayouya.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gt2iuaeuhav.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2asmbxdle.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2nuxcwvqn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gt2etmklyhp.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gt2tswzjnly.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2glcnpxtl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gt2ribrqoxg.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2qmqhbhxf.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwpihsma.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gt2uyhskznr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2besklmkb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2ejsakuop.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2jeximyer.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2rnmrzrho.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gt2aueeyalv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2zmwidwkj.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2qrzgisbj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gt2nbotlhjx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gt2nuxcelni.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gt2tarkjuxc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gt2hirpupww.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2ujpoqzcd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gt2ssyhmlbu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgfzy.top/Article/details/gt2warbkoqz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcfrkpsc.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gt2beuhfyxt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gt2efgtcckw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2tkwgrsvv.html


<!-- 参考信息 -->