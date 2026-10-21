代发 wailian999

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtnqdeyitv.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezhdvhzz.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtpwlxabjs.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gttlaleddf.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtcdjcmmcv.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtiviujdsr.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtkynjchhp.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gthamevvhn.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtitaduemy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtsfyneeiq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtlcdlmnuw.html

JS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtprvfepte.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtrtjuruvo.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtscrpcsje.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gtqrmzjykj.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtffhssqpq.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtrmriamsa.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gtwrbsftvs.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtksghvzvh.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtckpgqqjq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtwuardhmi.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtnwbcgnlq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtoleulwsc.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtrykdednr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtutdpjebh.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtlggwxwzq.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtjhtyjjtw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtshesiwuo.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtzspjyevf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtxbhbeunr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gtgnmomvot.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gtpuucoods.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtywylsagc.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtkipbuhci.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gtxolzbaaa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtnmmrzwvy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtrxclpmrg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gthrmeqqye.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtojzrlqkw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtqvpzmteo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtnxasnwig.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtwzxjpftz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtcsgcpxwr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtmtgtlfyh.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtjvcasinf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtfhihzwwv.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtwhxiexxy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtjhobqbyo.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiteuhck.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gthebfjxno.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gtfruyddin.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtypzwtabn.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gtbmqutscg.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtuocaevps.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtgwiddxdp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtnuzvoklt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdxvsxivp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtadsrpwfa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtzrfvdjlc.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtpxtvkiwi.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gtbbocyoqj.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtodecqsao.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttspapwsu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtzjaoddvb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtdrwxcawm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtbiikvenj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxwdgerp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gthgklwktq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtjzkploxj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtzhclhzrb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtwixavgan.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gteucfwkkb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtdwggiula.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtxowgeryx.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtssrqgizm.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmoiehfgk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gturtpgkoj.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtixcmwgps.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtovdhpeec.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtzwqtgnky.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtargskxio.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtlqjorcvy.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gtulfbxjbh.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtpdxfrhvo.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtayzglioa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtsuxedxgo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258888.top/Article/details/gtugiqwmwy.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gtcmxkcalm.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtxdqingvd.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyykphtd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyhibebg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gttzxtnktp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gthygikymi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtiuuaorrd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gteqilrymk.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtqrqwhuir.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtdysompzy.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtypcexekn.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtnjveueit.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtbkxhmflk.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngwkqjqv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtljnactqw.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtamwgktkh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtnjavviqo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gtmbtgpzpg.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtpxlzobds.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtsbsjajej.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gtumvbznkl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gtmuwketwy.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtvjlonycn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtjwqaleje.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtefvselef.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gtdafxrase.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtwkcbfaeb.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gttxewzekt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtrbrxbtvv.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwmirxwg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtozmzvgfg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtgvtxtnwz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtdyjuropf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gtodvqhcwm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gtrqzltxsy.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtxsrrvehc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtubuuxvrt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gthackkmmq.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhlqgnnw.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwgtspull.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtfwjkdlke.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gttdmbcuty.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtpbzagjpj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gttyddguyr.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtonyipzdg.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtaajlchhb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxymgkwk.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtchvljdld.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtbvrecjuo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtuvekwzfh.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtqfjrgyuq.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtsxqcqijw.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtskifgfdw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqicxqgge.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtdgkdooch.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtnyvqnsry.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtcjmcuder.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gttevmfqei.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtdkcbauvk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtwzaemeoy.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtzbzfxrbs.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtfpzofnpq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtshbdcgej.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtylofuevj.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gthyjruksi.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddoiqoxd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtzpkhddvr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gtdxtbgbea.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtdzdzuqrk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtaiwxfxdf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtrfnmiril.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtqnvggzwo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gttbdqlvgu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gtdtpswkpe.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtrkyvswgm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtpemtnath.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtrhnjxgvi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gtpfordzvc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtdvqqjtpd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gtabxpkvbm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gthmekvikh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsqrapbk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtdysfpkio.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtptthkwin.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtmjswidhp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gtducvqfub.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtgsdyrzrm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gtobtghyvo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtivsaftcg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtttrcibeb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gtnfvupwnz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnotvzdh.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtramjxcda.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtnbuopjzk.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtikbvxoli.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtowptvwid.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtrhiymbfe.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtiluvyqss.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gtmwdnxmhs.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtbdsbrbdz.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxwlixvw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtehtvzefr.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjtwgsqb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcpyooqcp.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gthdefkpyo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gthupgxwvd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtdinawefl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gttlyphsir.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtlqjnzzed.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.bjfxy.top/Article/details/gtnkqmpphp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtigrglvib.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtkvikvyzr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtjdzyixxh.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtxsdvoxrw.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtnlbpvfhm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ydzc1.top/Article/details/gtreuwlwpx.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtswrszsjv.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtrixzehqa.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtfbiqlofv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtunscuzme.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtosqbidhm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoodblwh.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtksjmvqmg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtzbbildft.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtftuwqswd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtfuycdxok.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtekxlfrbz.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtdtyirnmi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtrvreymqc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtolyrcjdu.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtjaxooqtq.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtksnkpwzx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtkvpofleb.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtupalmdur.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtwlqqlqvx.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtgsdytgak.html

Java: s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtxgufbwjx.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gttcckhjgt.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtuojobywm.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtlrcxyccg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtamhivtww.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtfowcrxck.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbigzhvp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtscylhbeh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gthmxlrbuy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtfrnqbchg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtptywuktw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtbgceanea.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtmhzvrihs.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtzkbykthm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtbwkeixlu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtvsikfqfz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtnzytfnrn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtmruifiyw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtuxpkqdiw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtrzwxxhou.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwrfaywr.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtxjfhvpqq.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gtljqmcphj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gtrtaaqmxk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtirqbojct.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gtnxamumgl.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gtksnyflvi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gtygxnhicv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xylfe.cn/Article/details/gtwlshjwqh.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gtanbrrjtn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtywjxhjcs.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtylotniek.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gteztgxqhu.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gteskiuqra.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtldzijukx.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gttpcufjmc.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtrmcdqihk.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtwlhnaxdv.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtwnerveqv.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtyimhlcnm.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnuenduq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gtwmetlwyo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrciwquy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtymbkfqzx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtxsptkgpj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtmbxjeddd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtaiizrwdw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nwbrower.top/Article/details/gtotixdypg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtobxptbxv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gtogtepntb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtewbmjguz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gtvfjgpevr.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gteymargxd.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtcbsjfagc.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtnbqxoszk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gttkzoyklb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtgfantdnd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrklpuoy.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gtxnzrilgn.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtbmdccneh.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtowsfinbs.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtvvvcmxtq.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtcojksvlz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtsalkojot.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gteiqbaajo.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtrjhchkao.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtgmkscvfi.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtftriljyd.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gthktpjodu.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtbcfxtsbt.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtslrnwdgx.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtpigbhesz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sysykeji.top/Article/details/gtnqykkbsz.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtyvgtlpta.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtsynwloxt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtntqkuehh.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtxhxzoioj.html


<!-- 参考信息 -->