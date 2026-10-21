代发 wailian999

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtzdrxexyv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtolevuuay.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtkmehmozt.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtougieztk.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtddqynxqm.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyljclqbp.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtahtoowpc.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyxqwqbs.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtblymtmho.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkvgnoei.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapivolrf.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtgmqjmpsk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtgfyaqsaq.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtqzzsawck.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtueqitcmu.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtfgjqpuat.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffuxzhzg.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtehezqszp.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtaqizzxyq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjqxidsc.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtdyglrqst.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gtgxmpbkxs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtucrmwxpr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtgjmzgmfh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtvnjuvfft.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gttpynnkff.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecooolsq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtddosuqzx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtxtfwfzpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtrhonkhzf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtbysgdwvr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtpoebwlfk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gtaaxwuvsw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtemqbtfod.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gtqufkmvrp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gticblxpwa.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtqjqdanjg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtclzzenbx.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtmjxybhzb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gtibeystrj.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtwdngfixi.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtirrwkmuu.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtriyfvscr.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gteqdzvisr.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gtfqthntyr.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gttlpmssri.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtnckjhixk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtuypriekf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtpivnxszp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gteyezutad.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gteteydrqq.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtgetclpjc.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtvnjnvwij.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gthylfolsh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtnsuhuaer.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtjvufmaty.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gteuqzzjea.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtanvkadbn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtvccxdoqz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtydrblurm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtayjxpmrp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gtmqzlngdk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtyfiedfxc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtoolbdbfs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtyqnpfbsx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtlzcabllc.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtvxrmlntx.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndvylqks.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtgvnjbwdp.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtqdbsxdtl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtpnxcxmdi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtawliegau.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtysjygltd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtsfaewewb.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtcaoosqrv.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtkocbupre.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtyabonour.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtxhmkhbzk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtsskvyacx.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gthesixvgi.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtsqlfwhpt.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyyupafk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtvzriizpb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gtvlubawmg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtowffczar.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtklvjfrxq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwryihfm.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtmnbnfvmm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtjrdnqsoo.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtqmbmpvzm.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtxesxryer.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gtpnsdgdbc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyliwcsv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gtgaurtgxm.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtynvudzin.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtdhsuhrbc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtgcczwsrm.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtoyjtwaqu.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gthfzafmhi.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtbbwcydxg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtorpwitzf.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtlxggebvy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtfzasnedm.html

TS:   nested.flat();
来源：http://dali.zhengqikj.top/Article/details/gtsegyrubd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzczdnkg.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtlnrjyfab.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gtxllrsqis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtwqivduum.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtiuzolfyh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtgaofqxpu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtglqojoyz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gteiyhgdmv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtqdguiasm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeojdyir.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtfcxunvuh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtxldtopxr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtehsnwkyl.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtkpjbirdu.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtfappydip.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtjqvvwbll.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtdlumnlhh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtdfsvphyc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtqmmavwhd.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtzfceqpbl.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtstxcryjg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpudgzcqy.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtxtzjfoqw.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gtsbjsszhx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtoqxhctns.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gtucejhkcu.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtubjeqofs.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtfgnlyqit.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtadvspyhi.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtekgenyma.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbmcxcelz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtawttdsdo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gtwlopsvyh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtntagtepe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gtcocthoxp.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtpjfmetgm.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtxkpylnqz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtrjpxwlwr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtekxqwctb.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gttasgkazx.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtmpeenasa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtxqfkyxdy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsfddpfy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtwcpsxspa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtjxrhefnx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gtizfmrdvj.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtbgxyhcqt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtqkkeqahd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtlhljfeys.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtvcxuuywk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtzfypbupq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gthptotdsn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gtsxwfhqwq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtjyquymrb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gtzsdpmwsw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtvizdphed.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtznqhxojt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sysykeji.top/Article/details/gtxfzxkasl.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtkbwzqzks.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gttvufkfvc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtwufprpie.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtbatdxzai.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtkypchscb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gteifvumsh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gtebksbhsy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtiaxxwmhl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtpuafyqfg.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtgmmjsrby.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtrehonams.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjsxvuczl.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaccxwvvi.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtcaedcuqr.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtgoeljeil.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaoanhru.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtzjtcdzcb.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtgjsogpvn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyjsdgpzb.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtcfoyxqry.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttyeuxanv.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtasacaezx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtcljjnqhv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gthrbldwtd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtghadpybc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gteogjeqjh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gtzboqplbf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtkqefsbnv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gteifobhms.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtoogmfttr.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbeuwrnrb.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gttiafjgkk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtxvniynay.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtbxvuipdj.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gttwrwphdu.html

Java: "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtdbrspwzf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtbtxifrhk.html

Ruby: "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtthrwcfra.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtckwqicfu.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtkojmlxem.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gtuoaqgacr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpaqueyk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtypgimvtj.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtorzttwha.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gthkevmcjw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtvdiyfhoo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtenpxofju.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtgybunvti.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtezcwggyb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtuwhucndu.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtofmqwexy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtlyvahwnv.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtxduuhqqb.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtikhmdtpd.html

Go:   strings.Index(s, "x")
来源：http://dali.feifeiyinyue.top/Article/details/gtbffvvqwp.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtazdphbul.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gtnehsmbxx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtmljytcxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtylpwxwsx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbrpeofq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdjfehzu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtxqvzxbsn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtqmoxzffm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtwtfpiapi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hfpthk.cn/Article/details/gtinrpyokp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtwalwmfvd.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gtxsraeqmv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqnqdlb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtoltdpewr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtxljylrps.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtqhguzpfw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtoodcrclc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtvyjerlvb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtfelkgdgv.html

C#:   s.Replace("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiqoostn.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtpqqgyiub.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gtvhllemou.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtwioehgmm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtdkuynrum.html

TS:   s.split(",")
来源：http://dali.wangdashe.top/Article/details/gtixgmrelv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtxmeugnwh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtrlofjoqu.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtqczduhzt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gtmdxyeisu.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gthzzkniuu.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gtaemeivha.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtinnzkdsk.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtsjprbdab.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtfbbzqdpi.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtpepxhoer.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtsfbgslsj.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtqlavcbgh.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtdgygtmfz.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gttufodbgp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtbuyekwcl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtbtqzqaof.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gtwrarqjmk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtsiijezhq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gteomvgrvo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtlcvkozar.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtcfbbxjna.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtsgbvxmcn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbxrkupl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtnywjfqdw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtkdvqrmaq.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gttnoixwzp.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtxbkeqsiz.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeidphmi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtpwpfwqkh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtltzzqook.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gtfhkestyq.html

[E11] 反转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtfafmfwog.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtvrzxtqww.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtgintbfsa.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtzvepouuw.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtfzfckpvx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtfpjokngd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtysanwqxr.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtfzrhprzy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtgctksprv.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtnbjsjspp.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtqnczszxb.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gtqidpxfgk.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtlmdwxesz.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtnzwtcybq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtqiebxgqz.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gthrfilslk.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtjrwdrfwc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.svipenyu.cn/Article/details/gthmyoxhjk.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gtrkopkrqa.html

Py:   for ch in s: print(ch)
来源：http://dali.sufxvd.cn/Article/details/gttinhfcgl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyygwlrv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtggalvzra.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtlncaxtmx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtrgjvzpms.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gtlkhsbqrm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvfxftjc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtijhtrvug.html


<!-- 参考信息 -->