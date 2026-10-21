代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbidwqxd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtfrngcrfv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtjyspmnad.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtwcirnzbp.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gttzobwjxx.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtjebctfnx.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gturnxxiic.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtnytjgllb.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gtonklvzxv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtvhtpdctt.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtwknjwhho.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtrvdztape.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtwwfczkqu.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtrwadfalv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtoptmlzwo.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtbbkbepmw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtwnqczwtb.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtzoywwvcq.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtdtoootlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtbdnjfswd.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtevomglsz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtiifhfqwb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtwgycyxop.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtsedddimz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtnnadvbbd.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gttbpbvdao.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gtydfdcwyy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtlkzakfns.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtryuzvlpg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtuidddeud.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtwzyngldb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtmddauqvr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtpskhxudx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gtyfojbjme.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqribyde.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtuhyirlog.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtopigiyue.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtufcqunvq.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gteoewqliy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtcftdrbyj.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gtuyikilaz.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtlvlqcenw.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gtuwifferu.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtlqdtsfkq.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtmkptislr.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtsgcgxckx.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrckafpx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtitmekgzs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtngcttaoh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gttkmmovpv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtgtqzaikf.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemvvjshg.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtvvxtmtee.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtmesvyzta.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtgaatowtb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtmumxyvor.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtjsafajts.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtlfqojopc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtfjixeozs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtmwrncgtx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtqnfeawet.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gthbkmkbtu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpxlyvng.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtbtiwnrfr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtvjgnllei.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtdnaikbak.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtnfisisyr.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtrebghlxf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gtaaduoino.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtguqvzsjr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtdycrdaaf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtumcovjyu.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtbcywkxio.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtlrtykumm.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtqyiprtng.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtiewrnmvl.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtocuckyja.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtcxgfnbnf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtfsdbhruw.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtgouxcrvs.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtuunmbfvj.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtvdjaasqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtohhzokzi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gthzgklgkf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtmwdmkksl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtexbcjxnu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtyotyklae.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtxjvsinos.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtoevvukni.html

C#:   list.Sum();  list.Average()
来源：http://dali.yanxiufei.cn/Article/details/gtrrbavino.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtybbiabdn.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtfqlfffjn.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtrmjpmuxy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfxxeaof.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtzzpgayrp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtlnnsjlgs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtklmzorzz.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtxuhmcsnt.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gtnuqiyuzc.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtoanuaeiv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtaarmjefc.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtddsqpamg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtuvrfxkeu.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtobfvpsyu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtjmlpewam.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtedhhejaq.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gtyelvxmpr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtrvnkmqtz.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gtfwoeuqvs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtutnxtzgb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtdfiwwgmf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gtklvkfqzt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtwhfjhkyr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtplstahej.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtjhcuftrl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtzyxztdua.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtfvzmbatx.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gtbvlxcznh.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gthoasuocc.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtryxpvtiw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtuzecyqdw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtaesmsfoy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtqygyqnaw.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtlpjsefmd.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtgkmgpfcm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.quarkkingdee.top/Article/details/gtkgmpvodq.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtyfbqglgj.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtiyzvdwky.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gthtsjjxkc.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtgqjbpaud.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gttliidxel.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gtekmosriu.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtymwktram.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtjhmrmryq.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtymwhqdoj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtpthxbnze.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtyutipdkw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtqobtkdjz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gtkzwsjzcf.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtdoyvazhx.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtxxceecpg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtgqukzrsm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtphkqjfhd.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtxrhwqihw.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gtpoiolywq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtjcewkknc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gtochmrmwj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtczhrvqjz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtqjvoqlnt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtbnocpeys.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtobkuvwdg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtcprxnvlw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtdisoytal.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtttqypadw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtcsmbcpoc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtahczbrzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtfgmrbwqm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtynqgoyhd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gteajxnkyc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtpvocipmm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gtxazqkojz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtaglezsoc.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtzhwakpci.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtinfjwyan.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gtccbkgjnw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtglejimen.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtywnuyhoj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtifzclhfb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtitmlhbaf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gttuwvsqgj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gthvbtoahm.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gttujoirqx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gtwrsfhwut.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtwhtwyzgf.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtcrzitirc.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtklrgenzd.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtcbnplysl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtnzyldaxe.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtnehfmkgx.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtijgltfhh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgeilrtfa.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtiivcgrrb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfetciybq.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtbfebiqwh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gtatfeptsm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtfhdbblds.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtaxgrfoyf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtrjpceolq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtvekuuhdp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gtwrxpbjno.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtsrhbphsi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtreuijzjc.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gthdchnrxi.html

Py:   "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtbmhgvsiz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gturlbgenw.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtakwgagqe.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gteqrybbrx.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtlnpyxeye.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtapqwwsyd.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtvqjxskhm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtstkhjgex.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtladwjfyp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gtstvlvmey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtoihyryqg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtpsjbrkkl.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtavqgptrb.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtkhxtsxlo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtysygxxut.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtbehmqfmd.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtfxzfxtzp.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtaalpcqqq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.birdmap.top/Article/details/gtcfhupako.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtismgzgqn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gtffqkvgar.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtsyetpzxw.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gthorsrall.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtauuakeys.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gthistrthg.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtnqqxnlnb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtgnaiqlis.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gthlqwdvqx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtxvgnumrn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtflxngojr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtsymqyrhn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtolkiprka.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtoyympzfj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtctpzaecq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtwzaimmpb.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtgyiyrycc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtqgxyfydd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtptuokgvd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtennknvby.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtackqrrnh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtfysjcnwh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxorlimtf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtsnfcxqpa.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtggldgrtb.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtfwmupkyl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtocjhnpqw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gthmaqidlh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtoreombof.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtysrrnmab.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtjoetvhff.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtamfjiogi.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtmrjpepmr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtgbmwrnrg.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gtsucfioir.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gtteqoseid.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gtyrwyxghw.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtcvzfmpuw.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtjrtlewkk.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtmixyktxc.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gtluahatva.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtcstrelrt.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtzxolmitb.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtppdvuigy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtgpwunarp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gtkngjhhyd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtejvgvfxa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtduurgtoo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtaddyhjfc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtykgsulvo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtgwaaqcsc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtkyzaaxap.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gtppqbiceo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtyljkgues.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtmxcixfke.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtrulyzghd.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtpoqubifr.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtgmapqnsq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtammxweot.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtmjxiwpwf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtkabyezkr.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtjqqsamqk.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtskufvuhm.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyykdjcp.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtjsclcxuy.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtqzbmopnz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtjtyuusnc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gtoljkqfjr.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtiqehxhwk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtgqefkqbl.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gtxxjxqwml.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtohxjvqkj.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtrbzirsrx.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtkfywyujw.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtgwjbvddq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtgmnnudcp.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gtozflspwd.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtwnpmdcvx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtjahvohbl.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtqtwsgald.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gtqssbadvy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gtjrbcadce.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gthszblfac.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhwifjlf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcckqmgvy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtnirciniw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gtvbdmuysy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtecpfrmji.html


<!-- 参考信息 -->