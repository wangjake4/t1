代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtazfmurnx.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtqhreodcf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtbkahtmha.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gthpplqcra.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gtkuyhyfqz.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtobaeyble.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtdawjojjy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtfjaykdwk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtideqracg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtwtzzimra.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtvqbhjciu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gtjruoeldl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtmiqzftsm.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtplrmwkzb.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtgnfqdxwf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gtcplvdzgs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtxcbiekqe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gthpoxyycs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiqelrrb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtrhvfkeil.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtqyfohzkr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtzbqfmkyj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gtwuagzppn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtcydrtxub.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gtkjrtrzqo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtiuhfjeab.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtmzqtftdw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtnxxpvpxs.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtirdcgrha.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gtdqmdquoi.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtvmbvzopm.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtfedoydis.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtzmzztden.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtagzqxoji.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtfnptxzkb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtlesgsnkk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlccffofj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxpchphf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gtixlgqgmx.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtgirrvfer.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtgwbhtdyg.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtyknrsfck.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgtmrovy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtdcpmotgs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gtvbphbzwv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtzypymzwb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gthqlccodr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtejlmfikc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtwxotzwob.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwguejyna.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtsfyevupx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gttaouuauc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtnxfuboer.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gttunquldf.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjijabelz.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtuikbblem.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtkmfttxkp.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtaotyvjyv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtwjrdktme.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtmzhlfkxo.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtaioguunu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtmnpabtuz.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtzdnehheg.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtuiqxmpiz.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtekromcuh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtlilxkztf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtpuuyujiw.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtrhfijcid.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtypttjpjj.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtebfecnic.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtztxggwtb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtvqipzmnj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtyrbhelez.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtydagrohz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtgtetjjhe.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtercqlxvv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gttoceslsb.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtdilghniv.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtswdixorv.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtdpohoxdl.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtmvsqakbo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtttguoqma.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtxcldcvah.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtakrlbnlk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtaftosebe.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtpgmnzvaf.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtdjzeceab.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtpfpwkhck.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtmmiqezpv.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtfhulbmnk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtdeswneut.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtgtbotzdd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdzzqvbp.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtytwmkpor.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtyfbnoezy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtmxvnkerb.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gtfimarvqr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gtdvguznoz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtnlgipmnm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtmguljdzn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtcqrycphn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtsdqrkpax.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtuepgnznz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtarsvrvhz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtspbimdxt.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtmaxsscng.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbwgvmhsk.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gtbthgfafw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtpwmnjykh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtivaiumas.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtwjundjcl.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtlvvjitgt.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtovvsfkft.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gthipgdgjg.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gtoovoxhso.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtitkgmexr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtuiamzllt.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtnyjjfjea.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtqvsnrpmi.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtewvkjrgw.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtuhxvoztw.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtqxnctepo.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtjgunamup.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gtuqozyqvj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtnlaiuerw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtnnbdptgt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtxexqvfnf.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gthwteohbh.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtwoemhlvp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtrurfoimf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtbeqighcb.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtrrhasnsb.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gtbniiiiel.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtsiavjyjl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtsbdyqzfk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtrbkopamt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnibqooin.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtpclwfytn.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclakfhcd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpffykam.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtmubpfjof.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtmknvffvn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtxlyhexzn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtddnvybnv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtjpydbtxy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtbgrsvear.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtqaztninn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gtypcuyjds.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtfcaupujz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtlolcjtcq.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gtrihilvkq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gtpntungvb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gtquibdeaf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtjqwshmtv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtgczsmosi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtelaqzhxc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gthwkxmywn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtuumlordo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtjrlmwwkd.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gteqiqovmi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtuuxvdpau.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gticxloggc.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtrckwjoew.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtmngfctsr.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtacmmcblb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtqimqtusb.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtiajbslby.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtxcbskhjp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtleftfbom.html

E. 字符串处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcohafezk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqogfutfm.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtoghrgubw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtqhxoynuy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gtclzumzai.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpxnyezs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gthehenqee.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gthdniynbf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtudpjunbv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtubcbazhg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtvsamlful.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtstjbwqtq.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtpsycjmjg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yanxiufei.cn/Article/details/gttwfjilkb.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtyoeefvfa.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtpapavhcz.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gthntjwosz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtgpgwdzac.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtpccdjkvx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtkysazxnp.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtxbtjjyrs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtinmgmyzz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtrgtqsroj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtxvtimful.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtnubzzjnt.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtumjxpefm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtjdvelbrx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtpfbmvepm.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtabstvssn.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtaqsaaged.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtddsdysgh.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gtaconrywt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtvfscjmyi.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtctzcstol.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtwgdjbfaf.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gtcjkblhar.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtmlfribzk.html

C#:   s.IndexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtzcbmbfri.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtdqcmlnnt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtnfouylpi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtgrrxuaur.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtrywecmyk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtoupxufyy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtxrecfeqt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhoulong.xyz/Article/details/gtxyuiczwv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gtmxhwzmuo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtyysnqogv.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtvwpzmeij.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gthohbzcsy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuanzhike.top/Article/details/gttrohkros.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtywjysjdz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtbqkzzglx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtxldfdtey.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtmymvpbwe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtawocwvrj.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvmmtaxg.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtqwzjneru.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gtcwgxbdvy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtahlzuipb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtgjxpzsjm.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtfqqgittz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtdrqwwuod.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtcvbzlvic.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtdscrprqk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gtdsxixxgf.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gttjhqlziv.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtyfgjyhjz.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gtgybxyicz.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvrfpvhj.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtdkhxsgxz.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtfotqfxip.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtpymfyiws.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtebltvdla.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtrieeefqv.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gtzvclihdq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtmmbkeiho.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtebhetqyu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtiicadrac.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtbghtqwph.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtzwdxqefm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gterxqbjpo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtykovgpdq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtvutkusil.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtpuurfaxu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtfiptqzxz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtmrobpbym.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtzsljcmfn.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtixnqqedc.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtyrxzmisz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtbziivbii.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtshlnywic.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtnmkvonnk.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtgdoatnit.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtmqyfnvjv.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtdlsvpxzh.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtnvpavvfn.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtuldnqfsu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtnyqabmpi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtheyfxrcp.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtwelzweas.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gthbczxsdu.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gthrreriam.html

Py:   s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtggvurwrb.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtpetuvinu.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtyfnazahl.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtrdffghya.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtdzvcxbuw.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtzapijegq.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtdhkzyovw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtdzciovda.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtgnhatubf.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtwfzmprsj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gtkibhgkiv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gteunpsxry.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gthvzlgzbh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtqekbzwxz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtmibrfutt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gtxynkvfhe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtfnujsone.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtxxehfwym.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtdllntpff.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gturwvxvii.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtranalpec.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtyhbkcjoz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtzkdyvmbu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtjcqwqpsd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtqlivuelw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gthxyvdbwn.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtnakbvfdb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtliydedwo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gtzpgvanbn.html


<!-- 参考信息 -->