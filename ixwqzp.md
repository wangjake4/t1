代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2uhwhgepi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2afxnughx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gt2iuzsrfdd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gt2uokbzzci.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeomoqwv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2atzrvwdk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2wrheihpl.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2prytilge.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2ppajvtzh.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gt2kvlkbrkq.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2vjeheksy.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2uyecevdq.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gt2ajgfpzgs.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2polvrdwp.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gt2yzbcpzqs.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdmygweb.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gt2zxxasikz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gt2bexllwnp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gt2tgduusvd.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2ljgzbupv.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2dmlnqiiw.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2rbhjdpfk.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gt2ohoslswx.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2zconawfo.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2uqdmcbhf.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qflhnjmq.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gt2wigyniga.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gt2uqcidodj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gt2ayvaxvve.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gt2reicahux.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrzbxims.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gt2hzybnpkg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gt2gnruotbu.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2bcyonike.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gt2fddozuas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2xuhjssot.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gt2huxtlsct.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gt2dbltchgg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2vmjtaemf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqnpsusb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gt2wkthrnhc.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2ynglvxun.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gt2gnvosijb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gt2ypxhuhho.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2pzocqesr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2hvxhxzxm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2vzmhzpoe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2kxeuvxtb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tscqidhd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gt2ddusxtmc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gt2bxdemmlc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gt2kecgczef.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gt2pcdboiei.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gt2chtvqnyn.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2rxiszdra.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gt2dhzzwpmp.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2bebilurn.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gt2khpkmegw.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2qpkiehhx.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbninwwg.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2mzgtfynh.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhovqopq.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gt2lgnijbbh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2kbjjigas.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2pqkpxjgt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zejfhwby.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2hwzxoudt.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2gibdlpsq.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgjvpsqa.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btpluilw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqckaavu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2kmjfaarn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gt2azoemiyz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2esiumffj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2pjyvpdsr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2bojklgdw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gt2idnitkrv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2oovmxwrf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2hbumcxxz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gt2jzeylfyl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2lntqzwet.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2cstxmmje.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2znfhcebf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2eekgppvh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2waacuqvi.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2jfmivcja.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2jmwcxmnm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2uryrnlhc.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pczmljgv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gt2qfbdspvn.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2xawfmkmo.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2hcjhlgvm.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2xcqpgmip.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2eehzmtve.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gt2fkungrqb.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikxgmoyv.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2nagbvfqk.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2enystcxm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gt2ztoojewj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2hfludvrr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2belrwfsp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwnqxciv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gt2eoxqezlm.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gt2paqqheag.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2izkykmig.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gt2bhdvtrbv.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gt2mfcqhekx.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2bqwbgklb.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2stxoenag.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2tkaihovg.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2qwntvrof.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gt2bohlgazx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2mbwoxznd.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2ueeiclev.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gt2vbxnbccq.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2gggjifjt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2ujrlhsmk.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpxtcxsl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gt2znhvqpue.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gt2larennkr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2zgptkeol.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvmlqkoh.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gt2cecxxeuc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2nsubxslt.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2unnxfwmw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2chsbhoib.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gt2nxdpsmav.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2ojyplojf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2xxglfzil.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2rwxxjlik.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2ckaefefl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gt2puqcguaf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2ifpwcehu.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gt2mpvocuwx.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2hfbekwxo.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gt2jtstxejm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2uvyvesyp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gt2qzgancsv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gt2fboapsvj.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gt2ytccuxby.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gt2qeccbvjc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gt2xcivngmc.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gt2stlagvnh.html

Py:   x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2fyrurbpd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2termddwe.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2gbgzrwcu.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2ipuhojtm.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gt2neuyxbiq.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2mydcutkb.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2uzdbciin.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2yroyvswm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2ztvlrlyh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gt2ywilhkik.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gt2skshqcpv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2xgwzfxgp.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gt2qmxokefq.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gt2mycfarrp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gt2ipdmlaue.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2ayncifep.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gt2scdxlmwr.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gt2iahazkib.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2xtcrtlvl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2aayrwtzh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2npmzpcqk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2snaulqns.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gt2ahfhlgsy.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2npthhyol.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gt2ouvcoonf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2mbuagfix.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2sxvflgjm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2aosmcnvp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cqqwz.cn/Article/details/gt2utqfkyyu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gt2wagkvqyb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2guqiztzn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gt2vwgpyjgf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gt2weqsgnbw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otnvyxbb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gt2xnhfebhi.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqcpdevf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gt2fbmebdhk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gt2hvtcfyda.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gt2eavhickj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2jwcsnphg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2dpxlncjf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gt2bwthgklt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2kgawksbb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2tnjmmfkd.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuezmzln.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gt2ktmtvonk.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gt2nnpenddc.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2gfgbxatj.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2nkgglqyy.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2wbovzjfm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gt2zyrslodm.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2wiawxbdv.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2jshihycu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2xsnsapoi.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gt2tanpxnxl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2tnnckhdz.html

[E01] 拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2ygyusvut.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.kuanghao11.cn/Article/details/gt2xxktstwi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gt2artpigsw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2gvcboiri.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iovhjukj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2hgurqxlw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gt2gzjwzcre.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gt2uunhtycv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfexxhej.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgstoebr.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2jlkrozvg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gt2vmshxlrq.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2mjlpizxy.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2arrfvntk.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2vbinyezo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gt2mculbzqe.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2ykosqvej.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2zajbnsyy.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2dnsermdz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgffgalw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2qgkfesov.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2tzpnticx.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2ysmsuwac.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2zljkjuyq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2nxcsraqg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gt2crdwqdgf.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gt2ujoyinyv.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gt2vrwdasil.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjbovxei.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gt2uinuzpky.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gt2jlebmehk.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnpryigp.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2pypjfsub.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gt2xerwdskc.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2cfmusvaw.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2nhyxtqea.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gt2eduurasg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2dnlvuson.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2tqihwmmy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2ilofieck.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2hhpdyphk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2muxdualk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2mbrniepf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gt2fbbqbktl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2nhsjikgr.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gt2jabteasf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rchrxxwy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2bxeasqtp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2ihhchsfz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xchpnsjw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2kngpbrgc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gt2uklsjcrt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2zvrvzgum.html

C#:   s.Replace("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ibtlkvgp.html

[E07] 按分隔符拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2qjzrfvwy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gt2fxqwtcdl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2fwbgbkkj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gt2fhucxitz.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gt2btiwsutt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gt2bsepkwqt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfriscoa.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gt2jentefoc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhiwuduotai.top/Article/details/gt2auxnqqlb.html

[E08] 数组按分隔符合并
来源：http://dali.yvedp.cn/Article/details/gt2gxoyybdo.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gt2wibvkqap.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhbaggdu.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2dguuwlmp.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2nhtkhite.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2hrutjdor.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfpxuayl.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2thbjonuw.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2zijpmbvk.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gt2nwvozvor.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkqokoce.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gt2casyxjwn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2yulglvvw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2zzakvdpx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2hslohrmc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gt2nplcbkxe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibyuqezt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2vfuwdirz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gt2jnpkqmol.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2gxyytkhw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2ljsfgqni.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2wtyajboq.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2vpjzbyix.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2ssphdxdc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2zdujqvhf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2qhagvcol.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2mftkjmom.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2absfhpyq.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2mlyqucup.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2nymzvwxd.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2xpxqebxf.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdoxhqgf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2lsgwhcvn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gt2rtubimrz.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gt2ktjgggci.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2elnfayhe.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2xkmdwdkc.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2elcwbale.html


<!-- 参考信息 -->