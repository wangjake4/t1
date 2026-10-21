代发 wailian999

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtwlowvqyn.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtfpuhgjfp.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtvevvahoe.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtcpmgnpfc.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gtbcnanhkk.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtscmjqwzh.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtlegjvtnu.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtjsdjggls.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtomvevmrn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gtxtnauurq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtrhpbnsdn.html

JS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtpyfhprwk.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtbofsuryo.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtumdiyhui.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gtqtmdpnad.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gthvjwpynl.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtouflxacn.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtuxsjneje.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtiujrujbb.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gtttpuqytg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gtabwidpmx.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtxhsdvxon.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gttdvifuko.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtqplkkgqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gthqmdlvss.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhnjqgcu.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtjmhjwcvo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtxkdumshi.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjilojwb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtczqwjiwp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtixynmkju.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtirktbklg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmuaxzlg.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtothijami.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtwbwcnzco.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtmagaroqx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtgpgqmojj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtjceuenum.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtlnobuvxm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtdbdhahfg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtbkzzmtsn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtprmfdyji.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtottccouy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtydydraqr.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtafgtnwvs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtayiynjxp.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtcmtihyki.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtaopluosn.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtbercrvgc.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtflfozjjp.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtmjgqhzvv.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbbusfkh.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtqbinkyij.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtgvytbeyn.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gthdwawmtb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtyzkswwuw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtvttokppk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlzyoxrk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtodazprmm.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtvzarlpnn.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gthdommggt.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gtxmlsuapy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtzuovgzfr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxwavgng.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtajfnddvo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtoicwdmkr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtqcuuecny.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtohymfxov.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtisoftjyz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gteapslytq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlcpukpm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtqskisete.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtqpyugevb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtzxukdpml.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gthxujurlo.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtrkmhipka.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtxfqeijay.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gttnfuwspl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtjanbsvmo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gthjdqxotg.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtkakppcsl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtnhnlyrwr.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gteunhsynw.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrwppsbs.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gthedesdax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtlylrpqdq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gtpgpgfwij.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtuzodccgk.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtvzfcksum.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gteyaxblgp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmaawczbn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtoqnpvhpj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtjiesgonc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtskgevcxk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtgyfzgmeh.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtozqtuonv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtrlarikby.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtjjikukqe.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtzezxfqdh.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtknbehgth.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtgyqeonde.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtlhuwnomc.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtulwflvbc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gtdlslhiul.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbmktodhp.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtebppcgel.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gtqzuxsvhq.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtfxxhczvn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtosiagvlp.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gtjjqflwmr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtwvqmshga.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtpqkypoul.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtfxaunozb.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtnheuyaxh.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtxkmzqfie.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtmzswwdmv.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtzjyidawg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbypmgyk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtglghpxtb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtdgsroxyd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtfoyqglbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtmkuppmhk.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtkuazmjjh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtvrfgwoii.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gtxaqohure.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtaphxxyrb.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gttcsmnfxb.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtymrtrpet.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtjwimmuxy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtnhdnqvhj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtqrnxaomq.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gthnmkdbdo.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gtgximpbtm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtzkrhtxxs.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtgzxgumay.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzfplwkw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtwnitigfe.html

JS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtsfnlkpwx.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gttthaakpq.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtomruafst.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtlrdeikns.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtmndwunda.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtdspquqrr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtfwwhhken.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtgufhwler.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tianlin.xyz/Article/details/gtmqhipunj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtndufcijl.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtvnzulwux.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtgvvpzjqb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtxcpyidda.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtaiznklsj.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtiavmhutn.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtwqoltnvc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtpyptruon.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxniojdbz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtfglqkryz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtynlnqosc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtnxwqnxeh.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtheeijdww.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtinjojvwl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtzokxfjyf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtvquxftnh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtbxokyise.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtzxzsbjvv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtmqthprfp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtujzkldjt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtptdhmowi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcvrgqqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtmdwgncyj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbenoumly.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtkpsgxdsu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtybkrlncw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtfzgvhxth.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtuhyxtpzz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtedehpngd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtkfbgcdyo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gtsosuqhts.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtqrtatccx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gtqdvjbfet.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtslyedffh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtnxrfwcwf.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gtolbtvtvd.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtcwqtnyah.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtahgtjvys.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtuqezzfht.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtvzuvrtwx.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtbuxlvqaa.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtzfhxottb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqgtvnudv.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gteiipyhos.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpuudnznb.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gteuclmgnh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtkziwuocj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtjusxdpkd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtonulvdzj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtqpokisci.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtqhuqxrfi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gthsbffpgy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gtqorvtimf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtqqkfdgqz.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtymoepdwv.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtnsthiihx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtnzzzqtql.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtpilulewq.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtkampxqtk.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtlncjuvnj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gtqpcoqjzw.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtxwidafyd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtckhqdrio.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtnvxhrzgd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gtvkuakqgt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtklthhkww.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gttfuftjec.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtbyxgesgv.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtizrutdqf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtblkssahb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtghqcnxoe.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtebbajjzz.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtcbfzlzef.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gthjmzgnjg.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gttrgojblp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gtymoqqedu.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtjragzcjr.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtmztrqfdl.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgfzy.top/Article/details/gtddddfrsz.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtdpiprxzf.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtxfchrtzp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtmniwzvyq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtkzcysiwk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtcyvzxmqa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gttutujbzd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtoqjayhxl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtbkswunbb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sufxvd.cn/Article/details/gtqwowhszq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczcpgplk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtqwuieimt.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtyefdlbtv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtmooalhyw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gtgkfjmunw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtintmrcqn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtmrjjxhoi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtgbqkjebe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtxctwpxot.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gthfnbjvpc.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtliqyktwl.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdfsxxii.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gtghvhdgcu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtizdmjcfi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtoieooavg.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtnomaylfe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtonbhggog.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtqnfzjebi.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaehbaiaf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gttdhjeeyx.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gtqvhxdxid.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtcdpqxewf.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtfutjgirf.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtxexnzbpu.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtiomuvnap.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtsjjswqfu.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gtuuilosfn.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtefzihkzk.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtglpjiwjl.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtawumxnyr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtsolptwkr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtzbwgqugb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtwbcdgyqu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gttgqveoju.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gtggzlmuag.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gttcgfxlmg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnajrlyh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtobcvuczy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtkgoohooj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtxfibmase.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlkihqfo.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtblzknjpp.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtxejjbddr.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtawigydoa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtwmqypxfy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtowtezkas.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shangyingyoupin.top/Article/details/gtcvnlhipe.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtauggmfsz.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtwxlrryod.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtdlofulys.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtevvqwbzs.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtpbezmfyp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gtpfzzfxht.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtqnhtvauk.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gteohgwxkz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtbxjyedzq.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtifxqgumq.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtyvsoifwq.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtcvcwgpfv.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gterzldkym.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtqcfjncxv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gtrkjwwoai.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtttokmpey.html

Ruby: s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtojkasubc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gttsjhkvcs.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtqypthysy.html


<!-- 参考信息 -->