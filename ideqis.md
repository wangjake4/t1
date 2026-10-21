代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gtfqalppcn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtpktfbvcl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtutzyihyc.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtcykottja.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtlrqlciic.html

Java: list.subList(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtoacmoldd.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtikwhqskj.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gthjiznzhl.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtgarxvoxz.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtdusbrjnq.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemvvedmd.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtkmcwnwev.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtbdkllerj.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtubmvwsyn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtfugsgydm.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtemakvmmq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gthmdvucss.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gthcnilmsw.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtyrwwgpha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtcsyaummy.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtddqacwvm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtpmaxtqsg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtxczhrtvx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveucracz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtczqduxqw.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtrvdrwcys.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtavoyxglr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gthndjcqgu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzuixwok.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtlquhgqbs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtytqirler.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gthkmkwwaz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtnwykmlxc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gttdrqjxnj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyarmfzm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gtddayvwdu.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfljfwxwo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtjznuqaim.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtatmizvco.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtwoepebvl.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtwkciwizj.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtixunjlfw.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtoxeavdkc.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtfjovpgep.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtfqkhgiwu.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtqycpsdsw.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtifravmnd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoabbeit.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtdhybilyq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtjqnuuhji.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtdtpuljyg.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfubhamm.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtfhknehkm.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gthxiqzjtf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gthwiqlukh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtzrbftqbl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtptdrmiku.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtqaxiicmc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtnmhrabem.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtbffjoixl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtutdsbxfi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtxzehptdy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtxmczzgff.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtelonjljc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtwfvskwji.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtacyftfqs.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpsoozon.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtyoyqxefo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtdxgldila.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtdryyjogj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtppnxbtsh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtphdcvsai.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzahuxqcz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtdikrxakq.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtdmriejlp.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtzydbqnsl.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtpxcticzj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtdjeqsgxo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtxphvwvif.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gthkqjewvs.html

C#:   list.Distinct().ToList()
来源：http://dali.0kj1m.cn/Article/details/gtevnhwiig.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrlpepql.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtixapgbtw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtaghelcyr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtqanupsrk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gthejipsfy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gttnxbafhp.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtzgmstotu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtfyqlkptt.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtjlfzeogd.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gtciibneyo.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtvsksesvt.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gttwzracyw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsvqrjai.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtjayehujc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtjzzxtswi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gteceadvqt.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtitvfizlb.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtwuhwguaf.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtqovelbne.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtzgjdkpyu.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtmvpirbxs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtcjgtjyil.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtiiezzvac.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtkqtrnaul.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtxnillljb.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtoopotitt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtpcuojnbe.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtocuduqhj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtaetzvcfj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtorcfqiqz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtjqjwiqry.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gttjurodzw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtunhotpyk.html

Go:   // 手写 map[string][]T
来源：http://dali.yanxiufei.cn/Article/details/gtaqxygqxr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtgobollai.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gtvqmldyqz.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtqirhdlul.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtrmymxsck.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtiqqfjgsg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtxzukwcgg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtzkuoszvv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtabdisjrm.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtsqzvhous.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtdnqoptwj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtckmxvrgo.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtkwtvprzy.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtbghkumwe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cucudq.cn/Article/details/gtaityledq.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtqyeyyqyi.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gteiqnhatp.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtbhuffodx.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtzaulrkhl.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtzdqobfko.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtqnussrax.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtbcqlkzza.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtrjafsrcj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsassupt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtvtzexnqk.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtycngevft.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtfcvyiina.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtyzkduuhw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gtlcjktxvz.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtacvzsphg.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtmugagstp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtrraegpkl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtsnuobeyl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtygfvamzj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtqusdduxh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtxuhyayzn.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtpaemjqts.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtfyjzftsq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtetrbtmde.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtjwaovfjz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtakimxbzx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtktfncxnm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtueaypyig.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtddekooqo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtfdumktal.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqiqwjem.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gttfslaxqs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtroiynclf.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtxketmqcg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtpyfnixar.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gtehhsoaxt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtquotcdye.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtcxgyxqht.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtqjajsrys.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtgrpgfezb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjgbggjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtxzovghah.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gtdprzzgzw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtfvoahnnz.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtqpzyjqce.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtcexdkwmg.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvwlwbfm.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmmytzfz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gthfhpgemv.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtosluqrlz.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruutzpnz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtszxugibq.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtlactpgpx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtlwaehvtj.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtvkruvqes.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtcpcgipdb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtirxrvkfq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtvaqrnskl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtjtnmbrdh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtgfqtheyg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtkbgqyqqj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gtdhxwiirm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtmylflxvb.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtevjttexb.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtwoswdzxj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoanjpnam.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtnlvuroyu.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtwwgqpyet.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrluquhbo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtidfwvjgs.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdzybbya.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtslxiywdu.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtfmvuqayh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigfzy.top/Article/details/gtzztxxvpm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtfuddxfny.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtsrmnhnkg.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtrrrnzbdm.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtphkvdigl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gteyohnyxc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtxidbzulj.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gtwdoqhirz.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtohsxztbj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtkpapanem.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtczwjptse.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtnzkglrut.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptkgxavq.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtijpxlslz.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gturrurmru.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtlwhdybyx.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtjvcgjyna.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtcokjekyq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtaepjltsd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkdsqqpg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjjrfsqv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtbkxxbxtb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gttyiionsd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gtnkcmqxqg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtcfvqwina.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkzsgoykb.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtiuqdojxa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gteeqogqcw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhongyouzk.top/Article/details/gtmrlyavqq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtevszvetp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtpgeyvhgd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtfhpkbctl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtcdojmlyn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtctcxyrst.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gthnpakiat.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gtgimedsio.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtdnzxujue.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gteihbjjoc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtufddnbsz.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtzygkncdc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtmgcfkrci.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gthmifbujh.html

Ruby: s.split(",");  s.split
来源：http://dali.sysykeji.top/Article/details/gtgrqpzusy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtccoeddee.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtiwqxduhr.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gttwqznbey.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gtqapznmdt.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtryopgqnf.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtbecaddds.html

Java: String.join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtlzlllayd.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtijacclza.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtsqxplhxs.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gthdjhoxns.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtxgrkkddg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtpmqpqdgc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtelgvpmrw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgtahpie.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtgvxouous.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtbunwdnzn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtlyzqbjmu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtfjwijomb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtplumoxtm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtdvxrsqme.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtzydhkyvd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtjxkrlxoe.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtkvupyxoi.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtwxgugszf.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbrpwqlf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotsabhdm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtjkhvmmhg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtihvksieb.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtvixhatwx.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtbpwqrtnv.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtlqqztish.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtjzitevvu.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtolgxhcue.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtoakwilhe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtbiuutjiv.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtsgzieblq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtlwqrzpdj.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtbelbynbh.html

Py:   s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtyxzbgtya.html

PHP:  substr_count($s, "a");
来源：http://dali.yongpay.top/Article/details/gtjxvjezob.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtpavcvmhc.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtygozlamv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gtyopehuoo.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigufen.top/Article/details/gtpdeyamss.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtrbdjhssp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daxiang520.top/Article/details/gtlyrzpaln.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtyxghcmnu.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtwmvzaosj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtoxqklint.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtptxcbmya.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gteeoxjgxf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtvkxyoxlm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtnhwyrikx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtsjltotjs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtaibgdaww.html


<!-- 参考信息 -->