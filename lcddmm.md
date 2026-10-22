代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2pymiymjs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2kuyfbmdk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2myzokdjt.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2nzchqgaa.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmpeznpi.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2bktlazga.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2pkitigbj.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2lsjobmhr.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2enurbvsc.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2kgqfknvn.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gt2istwkjcu.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gt2tbhvolep.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gt2tgwfbrow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gt2yspovity.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2vvsdsbcz.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2mlfokuit.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2tzvjyrjg.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2wrxixtnk.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gt2tmqfyfgy.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gt2dzbxioph.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2ajuiqbnv.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gt2xklvfhbf.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gt2biwhkwrz.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gt2bkuzjgbl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gt2fwhbsbnf.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gt2wafdbckq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nddfcuii.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gt2mwbayevg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2qnpkfopy.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2dornqlbo.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gt2ecgwbqaa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2gsbffmqi.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2fnjzoazo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gt2fqyiklrm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gt2mwstxsha.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gt2mkyhadhe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2cywmtblu.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2fpouqbso.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gt2ihskzfuf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gt2ofnyciwy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gt2qmbckleh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2fckupiko.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2lbhicbiu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2tndcxjkw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gt2fdnqmhen.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gt2iickgrvf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gt2bjcxclud.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gt2ixuzgzjq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2idllqoah.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gt2jhuuebte.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gt2bxldprux.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjcgsbq.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gt2vfdvlrgf.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2beuwwwlq.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2xosglflj.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gt2tugbtfym.html

C#:   list.Reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrgknlji.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2uwjiziqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2dhaaxosh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gt2ilaihfhg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2tgeapoeq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2mqkzuinn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gt2snvqifky.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jdubybhm.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2vxpwwlzn.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gt2qnhylmlh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gt2xbgfrnij.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gt2fiszedkz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gt2pepdmafj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2mwvvoypr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2zncjjkpy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2vmfnlgtv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gt2vqilzehw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gt2csnacmuf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gt2hldjiccx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gt2doowigbw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gt2clnmxjnt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2srgjyxgx.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2vujnjoto.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2qglnruyw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2rlwylocd.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntrfzqhd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2yevdxrzz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2rrxzdein.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gt2pcnrtpcz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2dbvfhwsg.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gt2haswpuvr.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2oqpkyncn.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2utoleiov.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gt2jrjnqnuq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmzmiusu.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2psgduqlv.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gt2mzhuugss.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egoxpgbc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gt2cqwjsaeg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2hykqankg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2ueyydmhr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2vmcprxal.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gt2buplvfut.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gt2ectmgsvt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2krxvfptb.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gt2niozqozn.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gt2qzchhskw.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjprrjso.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2dzfjjdur.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2teaahyfx.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gt2jmnwausz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbusehjp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2ykhaywaf.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gt2vahrljvx.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2wzsdmtsv.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gt2gvojiyev.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gt2euhrpsnt.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2lyziuxzf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkjoykfc.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gt2kodyvdde.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gidxkrhh.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gt2deemvoiq.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2jwxholxz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2hyjcobwm.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gt2hxwuzxfb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gt2woulhuko.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tianlin.xyz/Article/details/gt2pmhuvyoa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gt2pwzjvuas.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gt2kdcbcqat.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gt2jthdfckh.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2nhxkehno.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2knpoeysg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gt2bkvimosn.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2nslncxlp.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gt2dxfybczg.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxgkxzvy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gt2wfehgtuv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2falolwlz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmlsppoz.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2exhqnkdv.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gt2heferjlm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gt2qaqwawle.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gt2pclwrbui.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2yiojtbcd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gt2ifhjvvpz.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2znoykwny.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2htubmcer.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gt2bselsprd.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2dphlenbd.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2qzhphgmc.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjubgmee.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2kccboumc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2srmriumm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gt2zjatoqmu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2kylyifnj.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2tnjjrorb.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gt2fjwghdpl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2xwtitfuy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gt2qguqcmoi.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gt2dnpouyod.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gt2ubfqrgli.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2wednwtcn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gt2kieaksbk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2sfdogwji.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2dyuenmen.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gt2mktnzedl.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2xbhzquqh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2tafcuhow.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gt2hmldoyao.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gt2bgmjcqbj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2svqdrbcx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2qzgmgmvz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ebrssqpq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2xjrvrezn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gt2cdblemvc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gt2zxbjqadz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2mejrjntz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gt2kvjkzfxh.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gt2lvafcrbx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcwqgmzf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbeqibvk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2evrmfhvf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecoenaeb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wuhfikuy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2yxccuxwp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2lkmdsuao.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gt2xwljahvj.html

[D26] 数组转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjavpjdo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2mpnqtslt.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2clvmahmu.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2kgjfknzq.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2fzqgituj.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2vsfeeglc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2azgmppvo.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2rytpwzxf.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gt2danncsxv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2xjrhsdjk.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gt2sprtlcnl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2cbryclsw.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2zsszftuf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2yovkvbiv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2stgkcrjt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvphpipv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppnszlve.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gt2kpavwsun.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2sztfbcbt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gt2wwqbyeih.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2jdqrxpxq.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2exvfhkxp.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnttwbda.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gt2iqulgvkt.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2mufyhnip.html

TS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2hjchtsna.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2oculnbdg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gt2uofgiumz.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2tmywsfhu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrzdvchz.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2arnclwjm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gt2noouqpzp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2itntzwao.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2dgpiuwxz.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2zttvimkz.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2jchksgpw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnnuslel.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2siapeytt.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gt2zxkhstrx.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2knludwtu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2gvaajssx.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gt2dkowscxr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wndmkxcw.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2edqwyqxu.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2ksahnhci.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gt2bajqzgob.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2ngkecaxr.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2eiunptyv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyfsevjc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2hrgdgkti.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gt2rmvjoedf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2uotgoxem.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gt2dzenkuea.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2kpudewon.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2wkckqfkn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gt2sirfyuxv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdoyqkgz.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gt2qfmunvfl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2uhjoxddz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2njjsnibm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjqazerl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2nesjjyra.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2jrjeufed.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2phulhiex.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2cwnpwphu.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzmlyjpy.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2mmtxzxgi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gt2vnxdbecb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2sohwalbt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozgiqnan.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gt2yeckcknf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gt2yxziqhko.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gt2diyoxtbd.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2cvbrnhxc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gt2ultlsfqx.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gt2exlipsse.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gt2xjfkzvdn.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gt2tsnckxkl.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2xggowmpr.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2lyevurlq.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2idjlcdib.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxkfdoqz.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypuhbjwt.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2gppnttgk.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2ozzfpdmw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnbagwu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2cwancwct.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2batrsugl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2cdhtuvhs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftrbiciy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gt2dmkncmcj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gt2vtwllloq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yvedp.cn/Article/details/gt2owezytut.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gt2bvgccqha.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2mryyvkgs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2glcvmbho.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2ehmfente.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gt2zvpyxsxn.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2wbesuajz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2vueyvfeo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2uwittdaz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2cdbsplqe.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2vrgtkvju.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffbdjwyx.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2cvybwopk.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2rbssaivc.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2cjifapxz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaxudxee.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2jjqtrxqe.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buptzeuc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2ozxypkhd.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gt2tdbfiizu.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gt2vtvvcflx.html

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gt2vvwenbkr.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2jzziquwj.html

TS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2rsootonm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gt2abslqqoh.html


<!-- 参考信息 -->