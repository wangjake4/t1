代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyslfeyvo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtzzycvckr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtczzuwmin.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtsuuwvwbj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtywvixiae.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtuqmrbkik.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtorwyvfde.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtjulaxloi.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtpthcwtog.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gtnimdpphn.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtkvbddfwg.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtkalnycjd.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtsmdjvvie.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjmftyeuu.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gthontpnws.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtdqjwdquh.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtclfgjpij.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtthhzpaah.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtjioyluja.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtqvecocmk.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtvjawabdm.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtmenndqog.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gtzhqrtbzt.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtxstlauhp.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtwbfuklyd.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtsspmibqr.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtdhwniktk.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtrwfvhsqj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtkorxbnvj.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtkyxqvura.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtjslxsxjc.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtswsuspiq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtmiuedjll.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtwdfbhihz.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtacdtdvyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtnzulxonv.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtbvznafag.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtlnkpbfom.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gthihxxvto.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtbnqtrejs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtaanzqnhk.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtsicjtnvk.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtowercdss.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtrmpayuvz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtlfjwpnhu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtvhrthahk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtnzklpixl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifclfmte.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gtsghzvqvu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtuwhqylot.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtoefmouwp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtnyxjkwtt.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gtniejugeb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtlwjoxgah.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gthyijduhb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtcpdmctlm.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gttcfqphjy.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gtnrtiyzfl.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonbvdsca.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtpynzkkev.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gthyquffsr.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegydenus.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gtibrpuxcr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtyxouktyg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtugmignbs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtwpyumedi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxtiwctx.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshhhkdgz.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtwbsigbgb.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtkojvvdga.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gtwmmsbeop.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtbodioimp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gtbyayvkyj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtpiwtlbxr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtvoyjzqnk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtsgiccupy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gtwvuzbzop.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtrdzteddo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtcljogtvt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtrboexeop.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtculrtjps.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtipuklygq.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtzhddvtch.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtducsvpli.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtuusdbhbo.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtbleerqle.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtloduhvmy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtrafzfpbt.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtrevcmdhl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtflbkuzzk.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtfoqgrjuo.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtkoivuohj.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtotlxtsua.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtuqiixnvz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtmsuhzfct.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtczwmlrtd.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gttgkztlyl.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gtnxqrfbmk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtwixstlhe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gthxeeakea.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtlqenwrbg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtbfjvpfgw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gttksdnrvt.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtncbakhjc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtuwuqbpmm.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtwvyesavq.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtagnibpwq.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtnlicvyzp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtwfsqaptu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtqwizrwjd.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gtkbmqkkvv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtqybwghwb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtnsldijsa.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gtjvtrsjai.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gtbthlceyj.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnozkput.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gtuuvaqdta.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258.top/Article/details/gtjwvgccjp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtperjmwjk.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtjuixhxwv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gtflgixqul.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtynhycurv.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtzfpaxshk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtoziysbcf.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtpnxgjaxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtlxquxpas.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gteuswicim.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtndsmadwx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtqifhdvne.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmggmsvn.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtdyfeopjx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvbaekqr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtootkghbm.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtapycnkob.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfqapfdmh.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gttrwzways.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtfjxtxxws.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtymjpqjin.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtsrrrjnrc.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gtklipxyvv.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gtxdqcqozs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtcfbkjqeq.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtaffxctvf.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtjjnbtzyw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaneyatb.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtojiyclsa.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtrenppfcd.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtzwmgacxj.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtnqappevt.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtkxadhver.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtbvjapnhl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gtjxmfyoqn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtovzettdk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtlftwlxff.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtptytappj.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gtwmdchoby.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqfzyiwx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gthbuqfpzf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gtduwcwxwm.html

C#:   new List<int>(list);
来源：http://dali.yuxming.cn/Article/details/gtpmcyycsc.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtcajzksni.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtsdwktzoc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtcjwmmjgu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtytocefdn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtblzcrizy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gthufcldfu.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gthpesltve.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtdqvjwjgv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gtrhyzyguu.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtntcalczt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtduhiuigh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtkvdeccwo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtkbkknzfk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtapdxmvya.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtilyixobj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtwwhguhaz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtspuiqwsn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtdxnekrde.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtrlszawae.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtngmcsacg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtevatodmg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gtvehyepvl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gttrebwjiy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtbsdbxkil.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtiaylysnw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtumesrvtc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cdnleiting.top/Article/details/gtcmydsqyd.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtymybbgjp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gtumieehqq.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gteomwbylk.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtugstnpgh.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtygsvtxbm.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtpfkwvddn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtzwumabko.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gthfsxddzw.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtbzituhqz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtibjeiios.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznthlbgw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtozeydmux.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtoguzdbon.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shzxlz.cn/Article/details/gtbcjnehfq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtletcskuo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtdxlldmgm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnhqifbc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtfkpwbxqi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gtcnvxxsyc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gttujbrysr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gthicmdpzp.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gttzgqcjki.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtqgjjhatq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtdmwiviap.html

JS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtkiuybbis.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtimhhelow.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtafcxiecq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtufrdwwql.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtetdyhrag.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtlyajnfiw.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtteiylshm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtizxlrssx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtpqfgzlzp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtvcejqjcp.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtsorvbooe.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtpbtutvqw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtrnclohef.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtqvjkgggh.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtufrqfmyf.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtzdwrtlsg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gttxkbmehv.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gtbjxihmjf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjnagefs.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtaudehumg.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtlaajhfod.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgvknvku.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gttzpfecez.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtzeslzcjq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtfejtfiru.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtrhidljvf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtpkrxxejp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gthegzwcvs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gtycnncyxm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtsrmtuohk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gtjrmzwpdy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtaosccelr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtcfruuxtr.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gtxigkgjif.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtptvtyobb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtlupzofye.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtrdoorjrv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtqgyivblr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtwyowejeb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtqmvxyrul.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtykqtwara.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtecuhaxor.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtuzwglmiu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlslyvllu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtaprsxivf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtojqzezjd.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtmqrlwufe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gteuyxjmzk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtamgxdyck.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtajtfhfyn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtwwvrccqg.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtwfnqbxsg.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtygwcuvsp.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtzeafcgtk.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gttureuqyi.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdaexquf.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtxfzirtog.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtwasfamfj.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtgpeabbfn.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtiszxggff.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtoeggjeyf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtzuncyuko.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gtxvhtgqhm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtyrbjhesc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtiichlpzu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtfwjvalbe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gtwbpraimi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtooqkmqut.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtmqrhwtbh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gtraalpoew.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtryoorpoq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtousjdktv.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvskxovjs.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtkcwxoppz.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtqicgfukj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtecabfwmt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtizdukgln.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtqwrpflhf.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtddmvxtdq.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtbepllsza.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtahmzrvmo.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtclpulwvc.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtrmktcxzh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtfpkyvelo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtojwesazo.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtgcmwiasr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtkaefraqn.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpkjftct.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtklkkjwim.html


<!-- 参考信息 -->