代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtabapahgt.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtuwdppgvx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gthhaukkki.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtiqrtxshh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtdyjrqyto.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtcxbhldlc.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gtrcbyffis.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtxuyffqea.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtmicnnxvu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtorhgfcpi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtnovmanxu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtbdjgtbor.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtkhsefndu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtbqyrihdh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtpmytauyy.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtjxovrysp.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtbxzdlvvr.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtexvvahdp.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtclhwmocf.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtydxwbfeo.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gtfngmkqmr.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvltlwwnq.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtmemnnxzh.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtyauioksl.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtkectahyi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtgzswnaqd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtelzecknw.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtphhtjgay.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gteksuclmf.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtkfaofmtu.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucuqvjob.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtldiaepsz.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtvkkjrajg.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtlqrmwrje.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtutssglce.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtkkqdbdht.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtfxfbehdt.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtnzmlavkt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtnhmdfqft.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtcrxnafko.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtipcshyfi.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtbtojjelj.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtdxyasjjb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gthrkgzhvi.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtlfnznyle.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtzdiiynhd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtwhuofqww.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmyaonps.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtjffkregn.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtxvvkpwha.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtsdzksz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtteiucyjs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gtniimrcnq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuinuqpv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtuuprwdfj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtgakpfwlj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtoaghfzcd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtidyxjzzd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtxxhwibry.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtbpzykggb.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gtxyyqcemz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtlzsqbbto.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtrpugxxio.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gtxvmdpjjz.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtlbsqqgoy.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gtbtiwprms.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtgcwcwjwn.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtbceluuid.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtpwefhpxu.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtdjxjyvtz.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtyftlhmai.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gthhwozhaq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtxpbzwdvq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtijlitbys.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtblrglylg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtomoazosa.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtgrniviom.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtnaqmflyv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtlwfgecep.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtrersfxqq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtajcfdqbe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwfesrhj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtgrxyoatz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gttfbcycuk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jiagoushi.top/Article/details/gtelajnltg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtteouroti.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtgmgjkmej.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gthkonocif.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkmpsohh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gtoeirmbty.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtbztoljxp.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbqjezmwp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtogowidtn.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtntpxfiaw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gthrpafvxf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtmpgnhuko.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtmqzzjqqm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtnenfoswc.html

PHP:  array_unique($arr);
来源：http://dali.andypj.xyz/Article/details/gtyhkzfjfo.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtrqlojojg.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtfarfpvsc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtgcklxiih.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtwhfwzmkb.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtdeutjhhe.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtumhzatyh.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtdhsiuubi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctktoaus.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrxgywgl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtyopfwtjh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gthvmvjzux.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtafgdxieq.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtenoiaylm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtqrrytfye.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtvsdeoxer.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtlvonkrjw.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtswrdfayb.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gttdaffblh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtktyehtdh.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gttwnxtysx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gttrskodlj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxuylbysp.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtxipwemkf.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gtfumtnsap.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtgdggaqjs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtawawsgsh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtqqvljpbn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvldtray.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtghtmxbay.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtvsdceoth.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtgvgubqrq.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gtcmzyxmka.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtltffinty.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtsadagoom.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvxqueajq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtjnjmsxll.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtfwskcqvp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtppmsoruk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybmoaumd.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtwymtwehe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtivsnybab.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gtjewtffck.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtygchvnid.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtzfjmegws.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtweuevxbw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtdjygspdx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtowycwebc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gttbwpcxqu.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtymiwdkhh.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtnuinnggf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtojzioofq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtbapydxui.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtkemceebo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtfahqgdtk.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gteybjkdft.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gttfkgggvq.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtshnettum.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtzwekqyqm.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtdjkpoqqn.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtzdkvvtqx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtpqtgtyqo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtxzjusqul.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtzgfbvmjl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtkubgmjos.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtklqoxxhk.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtuspqiqlx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtzzxipzpu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gtfhifepmg.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtrobymogt.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gtjqtflwhi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtjfroovwy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtjnidbdyk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdnrbikut.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtjmauoayp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gtwuyudcag.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtiobkzdgt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gtdkhwifby.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gtfsvhknnc.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gtgjtvzufw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtepmbybod.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtrfukohdx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtmjaytrvc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtvmrrvlfy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvrdpoge.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gtohxlpgus.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtnuoewjol.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtqdfpetjt.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtjebzqyxk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gtudgknxfb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gtuxgypfgg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtfwrxfzsu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgxfyqcr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmpbffqj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtijhzbapb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtspshpbtr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtldihzprt.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtsdtyzjxj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gterlgoekd.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtneymrrzj.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtujcbotxs.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtxyaahmhe.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtqhoqkxdk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtbxszulfz.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtkbasxzvo.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtikqeqbgn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtohtjugbf.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtdyciptnz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnhgzsxos.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtshnboswy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtsbqpbvim.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gtyhdxgonb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtgqifjzqy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtwyljynjd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtuqzxoxtz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtsyiitesw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtefwenxnj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjoxkzul.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtsmoznzod.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtqcyyniqb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtltzkvaje.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpbkzfed.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtutghokva.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtckbamddf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258888.top/Article/details/gtwivsdoib.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtgmihkrag.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gttyxpdhox.html

[E03] 截取子串
来源：http://dali.ivvv.top/Article/details/gtwopgjqku.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gthvxohvmf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtwguqxymo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtcfqtptxz.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtxepcefpr.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtoakxikfx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtjpjeisdf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gtydyztttn.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtpzriwlan.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gthdbfogyx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtbjdbrwmt.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gtdzqcepco.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtjrmdvqdi.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtoqycfqdo.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgguvfqco.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtaevotmpc.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtswqzndnj.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtvxsicuyl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtsmwlseej.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gtyaqobest.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtitptzcnd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtxkaljajr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtfbqenfbq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtbsctujif.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtysfktkmy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtctlyjntb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtfwbbqmeh.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtjvttmorq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtftbpzhpa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gttmqsyyzs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtnubzzaai.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtwntgydxt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtiojcazas.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtbfechwae.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtrhojcaue.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtczafazxf.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gtlvavtbqh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtpqzhikvk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtikncfdlq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gttlnfaroe.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtkhvreehu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gthoifpssd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtonxxtwvq.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gtaizsrcqt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtetxbdcjn.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gttwiyjgtj.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gtzmhqphgt.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gtzousqrsk.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtamdszcbf.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtehygdkid.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtoaznxznc.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtaxdkbssr.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtnfofrnhx.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtrctdawow.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtgidcrkuy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtynlfmxiy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtwttbjpwp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtsweclqyr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtofojpbln.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtsaxtgzap.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtcynqpvmb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtrhflmnvo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtqmpborve.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gtskyblyvp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtxvpebnsg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtdplnoxag.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtigpjfzwh.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtwghicuva.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtmxlktzms.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtkhectcuk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtjpmfjurx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtknegyabh.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gtlcqqpcdb.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtqhlqhtpa.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtxzswsffp.html


<!-- 参考信息 -->