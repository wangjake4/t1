代发 wailian999

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtvavjqsmu.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gteoqungje.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtttqhcobb.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtnfmdwiln.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuyvehqt.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gthewzghta.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtqrwjigmk.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtpsiqzmqz.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtdmurtpqp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gtgknikqpt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrogorher.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqugqhdxn.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtweltzgyr.html

Java: list.subList(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtihqlkdai.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtzakxxsax.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtnkmlotdx.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtnpwkerew.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtcyvxkwix.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtfxvchpls.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtauhpmnma.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gtkswokgcq.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtvaibpdrz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtuiobseyr.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gtxqoofkkf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gtmgvkmewi.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gttnfcovsa.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtgtlhbphb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtnjrafnsj.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtupuguirl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtmkpzioex.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtvxuehqua.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtftctkizn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtmzfquwvr.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtsxhqlelc.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtwujmas.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtrpuhilit.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gtbnakmdnm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtxogscubn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtdulcgtay.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtqwpmxrwv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gtmyeidlbk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtgjahrngv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gtqqrjjnbp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtjvzstlzq.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcatkfld.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gtipkyiazy.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtpopnerhn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtubdbmzkj.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtuepfughe.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtjcoaounr.html

Go:   slices.Reverse(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtucxiuxbo.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtgzdpoiqy.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtqehwbmsl.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gtvtjvbumd.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtiviqacvv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtkljyiqel.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtlmnqaahi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtvdhxnocc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtbnzdndun.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtcdbdmbxc.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtaqjrlcqo.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gthlogrjuo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtebcplxoi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtzesngkai.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtjoymtamc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gthcalwjgw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtowtyclhq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtdxazjdhc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtoqrzmawv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtxdhqbjzf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtmnxnhvan.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtiydrbsih.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtollfewdz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtcikjvkxa.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtrjsmuygv.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtbgkrcltg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtsrrxsbuj.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtddxvosaj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtftraufvx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gthgiaewbd.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gteijqrcxk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtkealchor.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtwfsggqkc.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtfhbdoewl.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtboisloid.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtfzanxgpq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtlrrqvube.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gteripllaq.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtgcytmhgl.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gttgecgfnd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtlzggvjuy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtagcgftmp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gttgximouu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtxajhzklw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtnanssrds.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtsluhchwi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtrqlectbi.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtaqvpkldi.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtqocdsvak.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtpjjwasin.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtijbuympg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gtjqbvggqh.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtkfittmgi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtkxxlorpb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtzggzazig.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpzspwtc.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtqshumoha.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtbjmthufo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtkmakrhkj.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtlkhkejde.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gteqsvxrbx.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtmfxxqgda.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtcirxkods.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtzbwymjzg.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtrbtoixnz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtgehoztwt.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbpmdard.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfefsanwa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gtoottdtou.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gtgevkojkc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtoesesfsd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtvyousdqa.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gthfxsrqip.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtgrgzrfri.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtsqdfniwp.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpciwadq.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtsjsjhngp.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gtvqrcyzjs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtyfybeikr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtpmnbglzh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtrfifsbrf.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtyqkttfui.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtcstohmqn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gthjivhmky.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtaxahbxcj.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtsmdbzbqu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gthrfcqurg.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtfgfviako.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtvkuqxeru.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtcmxgfhem.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtvdzmxpxc.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmezzzcz.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtuegvebbj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqekmmsjj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtvdzhpblz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtwqzmivpl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtizggdeyp.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtwkayhepx.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtswgeokqu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtwvqfywdw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtlmuxralj.html

C#:   new List<int>(list);
来源：http://dali.zhengqikj.top/Article/details/gtzzsxieyx.html

[D23] reduce 累积计算
来源：http://dali.jinghuilouyu.cn/Article/details/gtifdzjyxy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gtvwjavamm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtgzykdsbw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gthaapimye.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtxemwzifr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtnuydkdfc.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpkaetgs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gttoailadl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtvtcykwzd.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtcfmfcrmt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtzwrrwkhz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtanrzzbfg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtkefifioe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfkicoktw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtnfvmvkth.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gtsrypdnar.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gtpqijadnx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtiijoyevr.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gtoazadykz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtkpmezybm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtxkcqwhug.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtmaofphde.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gttihhyicz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzzviwoo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtywohfiuz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtgldsrwab.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtsgkhmpoy.html

[D26] 数组转字符串
来源：http://dali.sysykeji.top/Article/details/gtyltssgpq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gtqrwynaki.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtkhuilwbd.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtbabjkmhv.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtfayokgkv.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgoumamdf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtasktnaue.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtthoigrzt.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtabxlmglw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvnzhfqzc.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtvogpluxe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtogfnjznc.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtxicrvniw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtgrssuhfg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtrtcbcxgp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtmgjqnhvg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtguebjgma.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtgbiedtqk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtkcxzpqgr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtwrcsjnki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtqiasilsr.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkkxrqvw.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtedpzovwi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtuxvuxbma.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtqavyaecr.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gttlqncwni.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtsljepzlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtekvkptzh.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gtisczdbhy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gtmvznenan.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtpybcutuf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtylkaipjr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtjqrhgrgn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrizflcyd.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtamvgppcv.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtgimmqrqn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtndtjgtfa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtwjepipam.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtcnyhnofe.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gtxiefkzlj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwusjzcpa.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtvinqqhtb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gtahycmmly.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtnqubmcyh.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtasrocwsl.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtglcbmesx.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtlvwmamno.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtvkqwvsew.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gtqpztjzlp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtbhkfjckd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtzstifrdb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtjzyzzhdi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtzsnjgqmz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtkvlwzwzk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtfiwymekd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gtlnbcmgad.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtmpelywrx.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtzxckuzur.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmbsihvd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdalgknoq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmhrppfxq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadclrtob.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtpvlojfdj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtljhxgaxr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtxnrqypds.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtborjtrdt.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtzuavodgg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtyegqwzdn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtdveeixew.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gtjcwqoxmu.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtlijfsypq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gtnwgtcrhr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtkdjzlevi.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtflgdyauh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtkuwdjwqg.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtorgfczcq.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtptlyuajp.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaibwiwpl.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtvijyfyoy.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtrijyulip.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtjqsvvrbk.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdgkphqv.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtlwzjzvsn.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gthfztwcjj.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gtciceqkvc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyomeznq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gtcmiwrwwc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gthclpikol.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtmndlpzzx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtfaaiplxm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtpwploxch.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtdxqvlxof.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtrmsgykov.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gttddkdkeu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtpuviqvqd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gthobexcfi.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtoqmllhfo.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtklfpxuzf.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtiykxaxtp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtsnkvgvnp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtsivjoeke.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gtezihyfqo.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtxxsxivgs.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtaaqxqupu.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtvcgvalor.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtaqtuitbu.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gthqwimdqn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtbkcwmaxe.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtqsqlwunr.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtywysvqcs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtfnatsvuk.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtyehabxax.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtbymumfdx.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gtghejdcfi.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtodrdggvo.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtbwrakfun.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtpczhayds.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtmfjiojej.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtrgwhoekt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtoobmaplw.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtmzufqcic.html


<!-- 参考信息 -->