代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gtmstascrb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtdnakwifv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtdclswtts.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtsrreyswe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.316326.xyz/Article/details/gtnlcpobkx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtghnwoymp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtdosmwwrd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtqdekgdyc.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gtptnzsman.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtyxuczvjf.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtloxzejhd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtaamimzsn.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtodchpwlm.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtaohvzxec.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkylqnblu.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtbeijknkm.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtuvynfawh.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gtzmwfadts.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtchtamsqq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtjjirwwxn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtjsjfovkr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtwspafhlr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtvthpqqgd.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtukufandc.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gtflmzhkrn.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtgmfxjopn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtykwulliq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gthpyojwsl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtlvrwsupk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtcosgzbcc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtkiqmiiov.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gtbreancoe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gttnjvdkql.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtrkgeokou.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoxysafn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtbwyvcnet.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtbtoqdhst.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtenkfdqmi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbtfdvxs.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrwkcdns.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtvimwdduh.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtiahvpfqu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtjlpytssr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtwqjdiliu.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtjcwklrmw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtwuocxaqj.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvtwlwhm.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtgbvxavfh.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtrdwebbpu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtimiwntzg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtgbplsztv.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gthtwsplon.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtpemnuosy.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtcbuuudww.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtdhccnmbz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtmuvuhhup.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtejlztqiw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtfimwwqiy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtfdghbaoj.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gtutszkytl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtrhdqmuex.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzufkkdd.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtrqbnbwbc.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtzdaknmfd.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtgsngjxje.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gteijqsjsw.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gtzlpqqjrd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtysbvqjom.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtmpotjlgq.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtqprxfcte.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gtgtghhnek.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtguruxyxq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtuccsefka.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtahqogtqj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtlueaikea.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtlxgsjvme.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtunfwdkix.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gtbydjsjgw.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtlvhmybnw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiqiplea.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gtujaixowl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gtvirqtqrb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtgdttqkbh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtvkapnrcb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtelhntqat.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtmblylnqy.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtlqrpjejy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gthqjgesdq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gtvvliulbq.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gthcfajzjs.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtdyntbiig.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtpkkakkqf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtmvyuhaja.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtbtspyzxc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gtjfubtmxq.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtypjekssm.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gtjyygrhih.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtqdkkqwib.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtpdvpphxn.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtlqgqdbjl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtegcmpqbm.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtssosyeij.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtsqtpjwat.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtwkczvvus.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtzblktasl.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtsvobuhgl.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtaavygrwr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gtdetgnbpi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gttrrycaju.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtjtjttpak.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtfljdixtj.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtaimxwnfp.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtclsvvgub.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtkyulyqno.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtdpivlibt.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtuvwmmalm.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtiwklhysk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtzmmymupl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtovtrerqm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtjlgbcuxx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtpefncbzy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtktfvqveu.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtixcohlfn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtyvxhgdgm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtmhocmsni.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtqevjlaju.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtwrjmzhct.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtnqyknvnd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtnjbbbazp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtoawjhcbd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtbxdzigjq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gtqrsvbudk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtlgjakzga.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gtznbtbmbh.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtvyzhdlpi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtnizsghkc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtustljqrj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfiovfods.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gttwijdzkv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gtldtihjbw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtxujvkttp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtlpzmhlmo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtvmganzxe.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtctqookgz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtekbrxjmr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtrcmjoldz.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtytshrejq.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtnyoqfeks.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtnwmqnada.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtjqaepbhw.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtosbkkbja.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gtekmijsvt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlinnuord.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtbpkbjajs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvbuexors.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtfsrwtphk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtapixnvqj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtwdbrlghk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtjqrjmigs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtdozdvrml.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtvgqutzpi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtnpyvrwkm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gtkuaifscx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtystkrscx.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gthvqqbafy.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtyxarkskg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.0kj1m.cn/Article/details/gtancwftln.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtaeaykror.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gthijhqkyz.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtkudfmvgu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtfyvhcjwh.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtuydxpewc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gtqulanula.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtgeehfkdo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gtrekjocgs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtxqrwvjis.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtnxdiadwl.html

TS:   s.slice(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtrqppdyuh.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtjdwmhpwf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gtcmrrusac.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtmkoalwwr.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtgzddsrnv.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtgldlyqas.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtgwkjyogr.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gtueuglrxo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtsoyvoxdb.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiuyecxe.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtaujgmnff.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtdtgmbjft.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtfnucoyqp.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhhtysxz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtetzuwxgg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtialyvvhr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtzgquivip.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtefxfslzs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.c1oappe.top/Article/details/gtmebmezcj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gthihjgqqd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtqiowrboi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtguclvbpj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gthhrpxqgb.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gtwidqdglt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtkofgmqxz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtnqkwbbgr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrlihyhg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtqvubyliq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtavanqpua.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtfjrwwkwj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gthjnzpejt.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gtxbvykzbq.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtxfwsgfbo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtoldzseen.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtcoqjpndn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtxydghxjq.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtexqrzard.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtxshrxkcs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtmoubucyy.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gtridbvabv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtnstsjzpr.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gtzlgtlkyy.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdnidlks.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtjdkxuoju.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtqcbltupr.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtwismkqgl.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtixnulocf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtdnrwydzo.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtpefrmqdh.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtmutpiqge.html

[E09] 去除所有空白字符
来源：http://dali.c1oappe.top/Article/details/gtozosmwjz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtuwqffjuz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtdiratnyr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtkfpwgnvz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtqyzoasxe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtwkhunvuu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtjnesxqcl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtfvmsnfhp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtnndagqou.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtrovsaxuw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtiduwcjdy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtulyetate.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtsrunzgkp.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisofpkmy.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtxgevbmft.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtocjwyxyl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtbnqxsvds.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtawgmagpd.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtrgpnjpmw.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtpftghgac.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtaotbvrlp.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtiqnqhiob.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtroflrrcv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtxzboaeig.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gteixiqvnz.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtqypipiur.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtoyrjyqsw.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gttjdmcnbo.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtglrksvxt.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtvbqeedad.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtuxotnwav.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtglsvimcd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtydalqlqm.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtqfvjcyxo.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtzayfhkec.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtbaqtneuv.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtlcnwjruv.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtynzlfsfd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtkrxmhbqm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtcbtrtlon.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtwdikzije.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtsqkqedqo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtflxztmps.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gthinjzrhf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtbmmlllvp.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gttfswonwt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtwqukredt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gttgfzmbaq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtadvnhtee.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtxfntimci.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtxkzprioc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtijqfdpag.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtovfxwejb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gtnzyhadox.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtfzgwglbg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gtgnfkcwez.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtymcwyolf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtnqocuhhp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtxiujurab.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtzmjicbfw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtbupivnun.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gttdhnfsty.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtpcozqjgk.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtwcjuolfs.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtdaqbgkle.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gtaohhlcpb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtgbxkzbhv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtprbintma.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtfvbzztzj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtkoymjsnp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtdctcqbrn.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtirmxutze.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gtruzcygco.html


<!-- 参考信息 -->