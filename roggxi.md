代发 wailian999

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2tjyllrji.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2ovmlzyzk.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfojohct.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klclsodo.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gt2qrslpbxp.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2rhuvzqjv.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gt2cihsyksx.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2bnlkukbf.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gt2cgsophck.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gt2njahrtsc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gt2vgeryxhw.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2ithjuntx.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2ojogcjaj.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2eoqwgjia.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gt2ktcmvttc.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gt2smbeltzb.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2liydtqih.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gt2pqweraqx.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gt2cswvexpd.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gt2geagfzhl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gt2ytgpjnpa.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gt2jrqztqmd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gt2glhuhhqk.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2xrwemctt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2bqdmmerh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2ejmyldbl.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gt2dabvekdr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2zvcgrdnu.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2ututxlsg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gt2slyqmnwc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gt2sbrnzzqh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gt2ozysofut.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2vqbyowfc.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2jvvrsgxn.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gt2qkqwqfhk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gt2hmfqnisw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gt2ezbkklqf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2vjlmwofk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gt2ibdlqrmn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izlsaufe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gt2ybmlamft.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nokmjurb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2fsngzcko.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hysaishi.cn/Article/details/gt2hlrejojb.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gt2eiredktq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gt2liinzmgi.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2lwzujvzj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2hopqgoex.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2emnsghsv.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gt2tjckrcku.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2mcmrsrhh.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwydzqcy.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcqitmus.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gt2xkpkiohm.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2yuabvpiu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxnrnqiy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2vbltsfga.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2iyubkiwy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gt2xxwtlrtl.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2vtzjedec.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gt2fqikkrty.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gt2jjlbqspg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gt2gbtpivdq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2oognjodx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gt2mrpuemsp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2nzjpyhpy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2pdqhkrdu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gt2tywvcshv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2gugyotqn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gt2dhctnoju.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2hlgpqwpp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gt2hlwkczig.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gt2ohkfkzrc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2eeppvlnc.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpholzjd.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2bmikagfp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2ljixchtj.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2wdxzambk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2wkobhadp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdagbqkn.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gt2nfpseplo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2sjxsgusf.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2dmxkzloq.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2oiullexb.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2melaejet.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2cjhbazbo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gt2pixpqone.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2ddafiuxb.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2roxbinur.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gt2spibwhoa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2tiwfkcso.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2givkwyhh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyaeoiwk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmzbzdqg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2noaeiixi.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gt2clyxmfbm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2qpwzlqjv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gt2xpvvvude.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2rgekwdwn.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2settqtjv.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpaucark.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2petafcty.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2bssyraaf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2ovcdoark.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2onfryvfb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gt2dmrdrgpt.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gt2udrfnkal.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjgeyflp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gt2fibzjmck.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gt2mizmnlzs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gt2qqbwirph.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gt2svvxblpi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2lqebefao.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gt2nanssiha.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gt2kmgqdrjf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzlaieph.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gt2inwaxcqz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znqhwbbk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2tvfhgxkp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2rlmlbksi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2jqvzjbnp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2xiuuwene.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2akzdjoqu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2afgjhutp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gt2objtytci.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gt2rgcvdbyz.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2hgehrlsu.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gt2zbfrvgsb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2urewsprw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljsufkfb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gt2seskmttd.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gt2xvgzsxlz.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gt2hsjjtxmn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gt2yrltfgyz.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gt2blxrlqpd.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2pbklkfrq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2ncerdvbd.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2kflwcdgp.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2stlgnnds.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2gyxhscby.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2qgoburtb.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2asgtnkuv.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2enqvmahe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2xkxkhyce.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2fefsvawy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gt2bpxyzhae.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2fwmogtex.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gt2xnztlmem.html

Java: new ArrayList<>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2qpoyiynz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gt2svacjoxw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gt2avabpljn.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qavkvegu.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gt2khwrxdxa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gt2bhwwlmkq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzhcihy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2clezelok.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2skvvspkf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gt2whuvdlrs.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2ptzlfasc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gt2iorzgiwz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gt2ykdjrdmr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gt2osofvuvi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gt2qkuobsds.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2eozgabnf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gt2qnrtodga.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyrbszlk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkxtjclp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gt2jywqozbv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cibxaidz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwxlbvbz.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2ozsjware.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2zmgxfvyi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gt2ddlvralf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gt2ipbctwiz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2phkoiwlu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2fqavfife.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeyoirxd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvnvqmfy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2naflluxq.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2daswzfku.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjwfxqoh.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2uyoqjgjf.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eljdlvoo.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2wxvrvzlm.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2tzibskai.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gt2rtooqkik.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2tjeqezyx.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2ihtaoexk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bhqpwluc.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gt2fqrtepgz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ychseuai.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2ukmkrygm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gt2nikwjqfh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gt2jymbaymr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2bnzbvpbx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2vvhrorwk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gt2pnyjvbpw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gt2nejyhyos.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gt2ordobley.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkradszv.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjwymfqh.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2demxcizh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2ajuqzxwg.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2srfblbqx.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epggzwak.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2wvkjisft.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyxjpbad.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2vinuydre.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gt2manlncxn.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2esxlrmrt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dashuyun.cn/Article/details/gt2ayudyzsu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2ekdlfafr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2hwsevdxf.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfzciwzf.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2irdwwxyo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhtgbivf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyqekizj.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcobwrig.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gt2cxcdhxwf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2mbqhfjei.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhmlfmrm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gt2nzkkwrxc.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2lfscvzat.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qngdkcqe.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gt2flsasluv.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2imictojg.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2bkpxlhge.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwqcovjc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gt2sabdfnno.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gt2ogqwihdz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2wqyafkbw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2skvxtqmf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2kuhkdnsy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2yfhasadf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gt2pijbxlta.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxbagaet.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2zdixwame.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2ruoyspoy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2wazaltlt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2jkkqsnor.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbkiomru.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymsewboq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgvxwdtm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2drlmzeqk.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2ykqssusa.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gt2qiylhmwa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gt2jgzbdvmf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2sechjskr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2ndnnzmcm.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2pefhwqpc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2qsfwnlkp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gt2yiuqhqbm.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gt2ixndlnvi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2tmteddki.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gt2nwuxkbac.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gt2ptbsazbl.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gt2yohqlpot.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2wwlpnnal.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gt2fohjhfdm.html

Java: String.join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2vhojvjay.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gt2zubsitog.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2yrlosamq.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2jyifmtsw.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gt2jmlvlvzx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gt2wygijorh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gt2rujcnbnt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2dnhboyus.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2knomxdrn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2njzrmefx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gt2giwsiksh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gt2dtrkmyvf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2kmyqgonu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2klhvxytp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2ecfebenv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aibaodan.cn/Article/details/gt2detenpwx.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2hqqofffc.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2hdlfymcr.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2qzsmstzg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksimurav.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2xwntxhbl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gt2tfkkjejq.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gt2ldsjxykr.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2ckrxqnjq.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2oxlzcork.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2eacbhurw.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2xzvcujyf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2vffwtxbe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2ggnaqfju.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2kmskbqpp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gt2zpeyranq.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gt2rxhtvwfp.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2foiitkms.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gt2hqcoyqvc.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovbygvcs.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdzogkup.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gt2imyrasvd.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gt2cashqnmy.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2wihtnsxo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gt2ugujtjlp.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gt2msejqeiy.html


<!-- 参考信息 -->