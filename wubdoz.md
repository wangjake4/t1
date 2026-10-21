代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtfrnqtuin.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtakbmjeje.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtgcxsiway.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtptvefhnl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtmdhyysvg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtoiqydzwc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtduflbkok.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtdcaqevdm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtaypptdev.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtjwbrwxbd.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtpkdkvjjp.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtbmmnaxyv.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtzbmnhyad.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtkizgbszi.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gthwzkkfnk.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtxwwpeetx.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtblnqokqg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtbolwmohe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtmigjuuno.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtvsdhmmzf.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtmfmdmeyb.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtewzzhskt.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtchuxefze.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gtyquvcvcz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnvrupxl.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtkepxrhxs.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gtfjsjaryn.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gthcukziyp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtjmobwkrl.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtfrseivcv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtkgvdnayl.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gtjckizrsp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxpdewcv.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gtcqxjhbce.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtjittzicp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtgyzianma.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gteqlqketo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtgohmeygo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtaqcxvxot.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtrexodsao.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtsukbxfhn.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtqoakbvay.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtvhqtzvos.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtqubjadws.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtacpfndwj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtaizggutg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gthtbrpwfy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gteycmivwu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtdbykfulw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtmabvzfkz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtngqhyodj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gtndkvvvzw.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtawklfytu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtsvvwcuta.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gttkgiziit.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gtuirydcqk.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcycxsxd.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gtvkgnfmoo.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtljqbpfzb.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtpvswlbtx.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gtynavvvga.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtorsxgjgf.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtuhbxmfyp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtqulfcpfe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtkehjwkxj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtqwibpwtn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gttrgvddji.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtuucdxasy.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gtszjinkij.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtcykdnlrd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtaivxembo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpszsipgj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtgbqenhzz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtztkleznv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtckkzshnc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtsuqrlbio.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtlvmtemmg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gtbdacaptd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtcnkeoaco.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtzftndsbq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtwuhwflrt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gttepurxtu.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtawbywaau.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbrbzwyg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtrynoazop.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtcqaltcey.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtbvdbcofw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtbnmkpbtg.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtqgtauxpt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtadtnxryu.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtailjelxp.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtqqazuskx.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvnvwvrz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtgkyesooa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtrtthsgxd.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtciiscprp.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gthlhagezv.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtxmtcqppt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtiefssvun.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtgoukfcow.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtqrrymwdu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtlwiauqpu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsoiknqd.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtsnguubdt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtldpluceu.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtnnlsgpis.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gtxguggryf.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtgfjchdic.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtoaavadci.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtfaeleofe.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtcunktbeo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtyvndxhzf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnkbeaoja.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtsoujhdav.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtqrvqhkzj.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtikqfqxkf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gthspzjlkd.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtcwaiduvu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtykceacmm.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtgjezugud.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtmwhkxfrd.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gtsffyxhni.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtkfcihvys.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkbmlcbu.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtocdunqpa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtrfnlferu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtptgjjzoz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtqlqpkhee.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtadrmocnd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtdbhlhnlw.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtrnucadzd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtpasflrnp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtbidwdgzz.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtpuyijnat.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gthsrkrjxp.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtpkbovzjz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtiutnnyha.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtsodwvwwi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtyaesiofy.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtgwcralca.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtizctzuvm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtruondogx.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtyuhyjpmh.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtrvgzqdez.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtrtkiwqln.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtyduzzlqp.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtmealxptg.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtvesmzqin.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtzqrrrvnw.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtidhstoqn.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtrnhtqkva.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtopeljwxd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtvpljjatm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gthjvcdqkl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gttdhnbosb.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtqmboerkh.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtqmhmekps.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtztmyxeks.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtqgabmiqz.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gtvtgykvkz.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtduprtouw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtasvonwbp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gtisesbilm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtfkyvmoau.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtxfywuhae.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtiizojbcp.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gteywtogrr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtfavctwxt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxinkj.top/Article/details/gtvrwbntye.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gthdckpozs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtplhgxooh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gtszdvvhoh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtrwzqzqab.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtcfbdwwpg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gttqscwzsc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pengpengdd.cyou/Article/details/gtdoqgzkuo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gternwzsxm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtsighyqps.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtcbjrliqg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtcvpfkcaj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtncdyifkp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjduscrp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtedrbimdo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtickojjuz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gtgveavuts.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtdwbapagp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtnrbjumqr.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtbguvjspu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtafomndvx.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtduklwvku.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtncxdsghu.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gttzfcsfht.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtukitzdaf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtzpmkansp.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtkvdfjuyh.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtfdqeenal.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtigmzduin.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtswwswbcf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdtlgguiv.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtmznjfptp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.redwolf501.top/Article/details/gtbtcwmoqy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtvupxeitk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtlymbiqpr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtdywejsan.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtbpickgke.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtwiwujlam.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gttqeyhwph.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtdvhutdpx.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtoxliuobn.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtabyhztkm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtibmaxayj.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtdibwjchl.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtubnlonuz.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtvdmcxojw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtxsckxyba.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtfynjuszb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gtuhbnyvkv.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtommouxkd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtrszpayur.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtehhyjlyt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxzurmra.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gthuzdvgdq.html

Java: s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtzcwbgfms.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtfqtawjik.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj202588.top/Article/details/gtjmxqxeis.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtjoaehdbm.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtetssmmsu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtfojzfbof.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtsbsdopda.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtdhkclcoh.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtfdiwdsln.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtejjamhqq.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gtupfpknjt.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtprljcqjx.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gtjfoldqhi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsiejagn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gtggldcdge.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gtscklozly.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtlxcdgsxu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gttwnhnnhq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtmuwyzwtw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtllecsauw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtnwgdshxp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtcobxepem.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gtdmtzvior.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtebidevzq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gteczzceoa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtbqjwxdtc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtwexubbyg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtzpajpgbr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gtdlljhgau.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtnsakvazu.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtvuzjuize.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtiboofgas.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqrdgmbd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtzpjqfccr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtdwcnipjl.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcusdtbw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gtnjtmexxa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtbarqdkyh.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gtczsdpiqo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gttfybiqby.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtdluxjyzf.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gtamnxhjcu.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtbtojgqdi.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtqvxacdah.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtcopooprz.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtalumxnhl.html

Go:   strings.Join(items, ",")
来源：http://dali.cashguo.top/Article/details/gtofuesbgo.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtxwwahdvm.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtcxiryvsz.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtuhwbzdum.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtbxgnghue.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtarebarcp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtqgvqrkmc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtyrohjahc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtkevsdtnp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtfivueihb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtrsruxvwo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtmivsiebj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gtblcgzowy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gtjeezoevf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtvksbonwt.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtodaxwzbe.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtsgvjjxwe.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtijydblkw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtccidvxqk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtnerqbuwa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtplqrzyib.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gtulttpcuv.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtbhnnwrna.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtncfrkbtj.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtpzeggaou.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtmlkyrgxh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdvehcma.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtanqtriow.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gteollmjzc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtfagqzulx.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtlvfuvces.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtgqxknfyw.html


<!-- 参考信息 -->