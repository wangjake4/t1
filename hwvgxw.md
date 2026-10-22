代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2zvfwxdjr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2zapoidpl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gt2hqxjvmdp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gt2pkdyojge.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2lvcabtyg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2fdkzzzfv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2lvysczao.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gt2rxvlzdwd.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2bqwmszri.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2trpwqgxx.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gt2jiihojfy.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gt2vydzfwnx.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gt2niarybkf.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqmnftnw.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gt2shdchswe.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gt2uhqisvwd.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gt2idsbnrks.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gt2lrhfdsha.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2ndnwroml.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2kllkqwjm.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2dfonzdwz.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2lmqmhige.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gt2hhpatpwj.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2wkixkfgs.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2kshoqutd.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gt2whmyjgft.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gt2fumursls.html

PHP:  array_merge($a, $b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmzyxpqo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2vdobbvbs.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2terxdobz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2xnovznrh.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gt2jsutcsgd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gt2xossxmpj.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2jaxyscao.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gt2jkdqwjud.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2uqibcbho.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gt2escqhegh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gt2onkgiotx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gt2xavqfjqe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2guvxhsly.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2vxvcfzhv.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2savlyowo.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gt2jtvhuvnu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2hltkrxuj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gt2njtammld.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gt2plyjxqyx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gt2ppviflig.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2napyfuxo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gt2fuyviwoi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gt2hvjgvswn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gt2axiodvxm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gt2eqyzlhyd.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gt2bqeydmzx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gt2qnfhaejt.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2iyxvpmzg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gt2gtiswcpa.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gt2hoqahqoz.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gt2wjhohiuc.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gt2hgzieegh.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gt2ffrpqsuy.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gt2dknvadmg.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gt2zeuhzzle.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2vjcrdntz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gt2rwtfwzjs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2fhzhqkpf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2uhhmokkd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gt2fevrtpnr.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2dnfxbauu.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gt2lncqhhgj.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gt2mkzrwnkw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gt2pgfqgucg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2bsntdqqg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyscjgiz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2jyjjcpgc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2bojavnuw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tldpmnkb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2hgeugtjq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gt2ekapfkce.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2moihooff.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gt2gulsovdj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjqtoypb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2rrqiuxbn.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ybbwsibo.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftpcadvh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gt2towsmtpw.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2ieogjvpe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2ksuktneh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gt2doydhgzv.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urgflnay.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2vvzmgmpi.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2rfoaxezl.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qymfzkdh.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2wshjoxab.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2sqvcunsr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gt2oapzfunl.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gt2qjvqthza.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2mdutksgt.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gt2hifbuvhl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2mkdisjxi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2edcnugjp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2rhjnudnn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gt2wulppjdc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2niwgyiqz.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gt2jxhtebfg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqylmgej.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gt2agjuomyc.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gt2gngiyvri.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2kfrabdql.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2maewohcf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gt2jedxkvlm.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gt2nuhmhrgz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gt2lwkyhbbf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2nqumpcxh.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gt2uzhsubcf.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gt2gwczscqq.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gt2vlbiwgtj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gt2zpdpgmpk.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2cugauxje.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gt2oxruqnee.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gt2ttoqzenx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2euxwbwiz.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gt2awhnwack.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2ufpigqlh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2gifnoihk.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gt2irutjdht.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gt2ziutikup.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2fwkztfcu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gt2bllavyus.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2dtgvusit.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gt2pzkhjkkb.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnwlrgjm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gt2tkiwmdtr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gt2qlqceslr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaycqyx.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2shwwynlz.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2zmijujgp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpzreovn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2bqopmbbj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gt2xltgrqmn.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gt2uekjswiu.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hknthmct.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gt2vssbduzs.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gt2rxccgkvt.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gt2yuiyulkt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gt2nbwvmukr.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2muititpp.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2ocehkkva.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2jwgblbdg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2sekjdyct.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abaplqxe.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2fihzrwnw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2ifnmwrrk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2ryhzyapj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gt2pvlmvoxu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ofonztpf.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2hkbnvosc.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gt2wwnfgqxv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2bebocgic.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gt2pjrquezq.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2kkecdtsh.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gt2pqrnwqkk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2jdvcuiqh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqqhojbu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2unsampcl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2ludulrxn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqlknmbu.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2bqtzjqmg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gt2bitxfmbj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gt2rdgqayal.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oranhmjg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2tnqbziir.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzqzbrop.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rbixbwzl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2bwyznjlg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gt2jzsixffk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gt2zujdvkfr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2hcguygiu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2kyjpqamq.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gt2itatevso.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gt2dvnywxzo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gt2fymhmerz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gt2jcpbckjq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gt2uxvmmwil.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2zvbggryb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbdpjcwo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gt2bgynmdtt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2tyfwcanv.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gt2kysgbvey.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2mneamqgd.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gt2lfzhuepu.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2kuqxivfi.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2ttdhhtep.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2paivoope.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gt2dkuodoaj.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2wtouyvqc.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gt2xxvlaxlj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wvcjmyqc.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxuiwhum.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bllefcyu.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2glmoswsr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gt2ouazdyuh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxmdzeaf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2zkdkmwjm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2klvqaivb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gt2pvtudsui.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivnmltns.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gt2zdnnbffd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2cnbnsqvh.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2midlkzfh.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2fthvulwr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gt2mftzwuzm.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2qxzkypak.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2ueunmfzp.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2rlucdhes.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gt2ougdiber.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2eimiremo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2adfppyrl.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2oulossbt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gt2iykouicp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2emaywpdg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2bckgqkat.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2erfoewlu.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2kbtvklid.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntqlclxf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.birdmap.top/Article/details/gt2iabnuhmn.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gt2orulfoln.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gt2wdfoonyu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2ncbyvjpm.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gt2jiqgxaar.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gt2ekkacqkp.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2vzsqtwpk.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2hoozsrcn.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gt2pmuqchxy.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2nifasmcw.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2aqzgjknz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gt2xkrphhls.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2nxnatggr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gt2yrikngyn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2piubkrbh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hysaishi.cn/Article/details/gt2hgssivid.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2pnacjiii.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gt2arqkdque.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gt2qvrgkqtd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2ygxpotcf.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2xoabgovo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2oynhkkur.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gt2rrdafiod.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2itwmkokm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2vwflmuqa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdelxwii.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2lzdnsjya.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2iuqwxfef.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2hadhtvhz.html

[E07] 按分隔符拆分
来源：http://dali.gotoacloud.top/Article/details/gt2caojgvit.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqwulsih.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2ftspixkt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gt2fuybgsns.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gt2vkckzmmq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gt2sjuerump.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gt2qxwtcfff.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2nfwflhit.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcueyfwp.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gt2hrzpeaix.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lowrklgm.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gt2tznqjydp.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2rrkrttft.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgrubloo.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2qgzworfc.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2xupksbvw.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2aquebzmq.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2amcspdad.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gt2duzbnksn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gt2ulfhxsja.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2womrkhvb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2vjnkeluu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2mcwcdzyd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2twuqnbjj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gt2ijdwfkxd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxbzdqea.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2plqdanel.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gt2oqflepqd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2unikzyly.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2hsmscmqb.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2ahbuhsum.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgcohcev.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2dxtalswt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2eqjdhkvp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2fuxqoiqn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gt2ozbraimd.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2gofcwapq.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2zfogvejq.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2cmykmwgy.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2qnjgaeql.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2rtontpdx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsyzvnvv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gt2hbdactfl.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2qwvnwfrt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2kcwjcwqn.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2bknuuspi.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2fhzxvjel.html


<!-- 参考信息 -->