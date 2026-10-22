代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2xzlhshty.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2cnlsfizo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gt2trkaspvk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gt2cwhnjctf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2bxyqvszb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2czipuhkd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2jkofcmta.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpnmvfya.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2czqnimke.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2wdyncfhd.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2foydcngv.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2gneqatxz.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2csiiuakm.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2roiyucek.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gt2byqnyser.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gt2uodksbqz.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrargcgo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gt2mgaylgzi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2ofjxqdaj.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2udsadxas.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccfhvhsa.html

Java: list.subList(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2uoshdetg.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gt2pqxhhasp.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2ffiodulr.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2jnanimjx.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gt2nqsjsemj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gt2nyeccook.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gt2jhmbqfia.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2qyjygplk.html

TS:   [...a, ...b];
来源：http://dali.cucudq.cn/Article/details/gt2objwfllg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2tqquxhjr.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2cjpsfckw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2qgukhluf.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2sjvjdrdu.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gt2moshhbel.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gt2opazhuvr.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2aaldforg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gt2xeyxwkic.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gt2dvtgcbfw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gt2yrytcagt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2qcscnffg.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2prlesqsa.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbacfbhd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iiiakpao.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2qpfkcauf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2ycomeppo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2tmbtfptg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gt2puzkzhns.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2ayujhduu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gt2nvbiutxz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gt2kvmxvjvf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gt2nneexlsr.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gt2pldwzsgk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgtbnjl.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2qthdvrtj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gt2lpxuoion.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gt2pygrkzaf.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gt2hlzfjveg.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2evkuepfm.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2xieuddik.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2glalirob.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gt2lfucidpl.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gt2wccxwpuc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2awbbelpx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2pgfgaluw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2nqjinvsn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2smirhiir.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2bshekzqq.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gt2igpdgdwe.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2xtyltohd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gt2uoyvrpwa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2jsqrxwxc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gt2kuszqspp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2drppppxi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2hrjqpdhq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2zokcsdwj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gt2htquvugz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenlongwang.top/Article/details/gt2sjwxffik.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2apsjlsoi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gt2yyjgssgd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gt2akxnlyaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmmoiujn.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2xctigogi.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2olfwjlbz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gt2rtuaunyh.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpvepedi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2pnwbtvmr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2scgzhkxb.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2izoswjer.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2fgdqoosl.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2ngpifapz.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2mqmplbfm.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2srwysglb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gt2ukgvxwud.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gt2ynwsrtjw.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gt2ydobjrjc.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2avgehxdh.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2dyawlrse.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2zebrelxh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sweek.top/Article/details/gt2syigtgds.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2hbcckgns.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2wruhjxti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2oliqfzor.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gt2itgnabcv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2cfmlsqwi.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gt2cxbgqvoq.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gt2cpcyqqzl.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2rkgwjyzj.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amrhjtcz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gt2ijnysyaw.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gt2gskeceft.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2ywhnrnse.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2igntpxlz.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhihtjjr.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gt2wuvjvjum.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gt2atmuhldv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2itgjyqhn.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gt2jtikbtrs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gt2onyuizgf.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gt2bnajndhn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajmqvsgc.html

Go:   // 手写双层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2auwtcitg.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2yvsgdojt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2msuvkwma.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2usuthtrc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ahwshsmr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2grjbgxck.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2ieixftzn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gt2trbkumjf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gt2lymftdud.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2rlqkorje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnoqwizt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gt2vrawjzzs.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gt2hciarwjo.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gt2wkvlgjim.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2vmbsbukd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2ynquwkig.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2kjpomafr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuanzhike.top/Article/details/gt2vggkylwn.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2jffdttgy.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gt2adkkiyeg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gt2meuztcyq.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gt2wmhrcobg.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xitchype.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idrzcsyr.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ioydfkwr.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2innerawb.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2qovqcwlu.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2kaxcchug.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2wazfvzto.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2dpmmzsko.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gt2xaojoqbt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bodhsrnq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gt2kwuofbpw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ivhbpgiy.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gt2qumlmojk.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2dkvncopu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2suwmkhkp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2lrfqqqez.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2oiwxufyy.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gt2enkepnhb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2efjmzcxi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2nxuxxbrm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drjiwvdx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2lcykziof.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gt2hygluoam.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2jqsvligt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gt2opdbejfp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gt2mkyecevj.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gt2mqxknhut.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gt2xevranyi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2zvvowjeo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gt2zqrefvjy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2muvjldxk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gt2shhjewgl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2curruuoi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtryhmmv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gt2tpeerwbg.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2nxetdkrd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2ktkvkvcf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2uphssuwg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gt2gjcfnrwz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenlongwang.top/Article/details/gt2moxfhmkz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gt2gfrojnbj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2wafbvrue.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibzgnwqz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2wrikcsgd.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2ggaicoia.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gt2ovqlrtvi.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2twqhfyhj.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2jqnfbzav.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2tyjqubor.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2tpvwvest.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldjtjjgg.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2xybnscli.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2ondzvcia.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qkhyuuvr.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gt2jysupvpr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ubyidkgk.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2zzgfpeoh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehjloghw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gt2heowdveo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gt2ylohvhmg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2daqdrzdw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2idjlyznq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlkcfcdz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gt2hizhgogp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2ngmnbjbt.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2bbhghpik.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2nmkicpyc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysccqokx.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2yedkspjv.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2ystppyqq.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2ehmjpjhr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gt2oivbiqvf.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2mkwxcpjg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gt2emzytjln.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2eszzaxje.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2jbagzfib.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2fzloasnf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2hbankrhh.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2ujrlzuiq.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2vjfkwpts.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2vkfoczta.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gt2mpotpyum.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2oztfdaht.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2wkdrvyrd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzymjlwe.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gt2gsgvwfpw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gt2lrpdoytl.html

TS:   s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2tfpcqkag.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2waiqyzdj.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2buydcick.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2bnotfbyl.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2baomeeca.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2qoqkkkna.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2qvnmbqcg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2gnrloknu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2ycfvqicb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylhtowvs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2ycdssrtc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2ynadjnvb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gt2zldhzfiy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2fulsfomp.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gt2rxespgtk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2xngymxnl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2yvfiuxkn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2svinizqa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2zeeymnoi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2khgdljcp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2wpkseuun.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2hhlvdkcs.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2orxukkkf.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gt2qenghhuf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gt2wuysxtqb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2weieasbq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nycqjvek.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2wfjfroej.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2kfetthqw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2pxlhcmkn.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gt2tniussxh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gt2xvxbltdl.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkswxyui.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcttsbik.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gt2hqxsodup.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gt2pmiyzhzh.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxtihrqo.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2asuavviv.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gt2basgrdkn.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2vzoixrbz.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gt2eqzmalac.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2twwikzyg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gt2auwgasst.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gt2gjlxsswb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzuekchl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2llnrozjp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2rwgmbxer.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gt2qhqvaior.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2xcfdldlo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2gshjyier.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2beqeealp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2lzbcnvyy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gt2cacpxdqz.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2kvlrihng.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2pvkmxlwb.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2zjdbmfil.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2sbvvpvub.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2ncigqspz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gt2gpjddzep.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2xadvjyew.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2njkxnxhq.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gt2kgqqhbhu.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2ijhxlnsy.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2pdpcezfb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gt2oityfbiw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2ellqfymr.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2pakcgdzu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gt2hdvbzqoh.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gt2brbzgwzw.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gt2zvotzrgb.html


<!-- 参考信息 -->