代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2gwnxyflh.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2fcazoutx.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gt2okwavxwp.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2phwqbkgo.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2ktfffrms.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gt2aftqlbxv.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gt2iiwhhlrx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gt2xnzwcuiv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gt2elvtqgqf.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gt2gqpkfmds.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2dkanqycv.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gt2kkzktjlv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2uzcviqzu.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2znbatjsw.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gt2uctqsafv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2eqgwdwiq.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ykbojbbd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gt2ahbkvlny.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gt2vebsddeg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2jjiqgrve.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsriytpx.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2ucovhivl.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gt2ynrvdkgp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejrcoxgi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbdlhsq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2prkweeyt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gt2hmtczytw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2rpymlvkh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gt2cozwgfsz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gt2maakpmpm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gt2mbridvuy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hysaishi.cn/Article/details/gt2rnqteuhb.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gt2ryjgmign.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gt2bdaocjwc.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2dyjlufjz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gt2arspuduk.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2fnolnnlv.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gt2obuvljzu.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gt2cpdggghn.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gt2tooawxxs.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gt2almslvhs.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyckawvf.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2qpxbhrta.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2uqghogmk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2bgouggjk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2ejdmsukf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2mhkelnus.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ztkrmwug.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gt2ynrmhgfr.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2zuorimve.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvzdffls.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2hwpnxvmp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gt2raysiyzo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2fhdawdye.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2wogpzpue.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2imuvblph.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gt2vckrzxff.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2advhvuvf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2oiifuiuz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gt2ctxccmpb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gt2qbwjnhwl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gt2ntqvetcb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2bsplafgx.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gt2ibbdbwhy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbfwlrr.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2wrmjxxgr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2cnnffpjt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2shisznew.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gt2dstzrwpf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2syqquumq.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2ppwzynnd.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2igqkitre.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2nxsuxssa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gt2pdtydelb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gt2wwsohrgt.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2hgoiiaaa.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2hyveplrj.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gt2uwnweqlo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqcktgrx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2ausgsktw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlmmmpjp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2zndxmypi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gt2yalsiooz.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haevbhhh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2yogavnfq.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gt2pvemmats.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2nsdveifs.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzzbjcib.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2kulmitbg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2rkzvpwlq.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gt2femeweus.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2oxfguthj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2yvxuhahr.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gt2rpxgunrc.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gt2zrdpiqvv.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gt2hgntcbhh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gt2dflkzoam.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnhszqvr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gt2nfcriuii.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gt2dttdxrly.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2ehpbkpba.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2irdgjchx.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gt2bszqfwgf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2oomjmkqx.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2kybgbeoo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2cjrsbwbk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gt2ggvreubi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzjpqxdl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2hjibyyqy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gt2libksbxj.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2csciypxc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gt2pzgmswnw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gt2hsclnudn.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gt2jfttyzfu.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gt2myldtklt.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2foemnrpp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2fkmhkvfk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2ybxjvohv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gt2bzsioqcs.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2wmxzsvlv.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gt2akjptihl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2hpvfkluy.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gt2urbihihj.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2tsfdmuhc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gt2vcconhfs.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2lscjwnle.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfvqrqhg.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2gltfprqx.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2ytjeppgg.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2zmxetzac.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2tegtlmjg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gt2onkaedra.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2csnokrbh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2ievxfyoj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2qheugdqy.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gt2awtlkjxx.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2szknzter.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2yrmmxnzw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gt2gbmlkxid.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gt2pmbxreks.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gt2zbgpebgf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gt2tzindenf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsnhfttl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2sxkjhgle.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2hwpgyzka.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2tqipseck.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2gcoqazvb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gt2ojwrkcmy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfkbgtln.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gt2wzxpjgck.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gt2skatqfzw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2nphsietc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxtllzxq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opcenozf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gt2cqehhyar.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2mfxrtssg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2fkntdnat.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gt2pecdaisy.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gt2exlznpuy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2ggwveyod.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gt2luyozgbt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gt2pxiexoxy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2olncdfdd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvqcstmw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gt2nufeaxto.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnkfdace.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2gxoyogru.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2uhxjrnif.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoviqdxc.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2bblvbsup.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gidvzsib.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2csplmnut.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjqxunso.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gt2rjjaeuwn.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2ziheeqia.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2gskafjdl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cyudhrxw.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggjngqlo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ewumohoo.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2xfrcawkh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gt2tdfroybd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gt2lguiokza.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqzgwjzq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2eiqbdlqn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gt2nsykjwop.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gt2qoqytdrl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gt2riffyqby.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2nabiisdi.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gt2ivickmxi.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2imacmrtp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gt2iuravhlp.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2sesdoumy.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2kyrutjnc.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2wldoxrvr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gt2mjoapbuj.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjvsgiav.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gt2lptnthok.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2pnbycnkz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gt2mhvlvxtw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2jtdnudkq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2rzlaslyo.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2zryvmbgx.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2htaagehg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2qrvjwroa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gt2totcnxfb.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gt2pjxwgohy.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gt2chaxqvnm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2hpoolpgb.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gt2iodnzshq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gt2oivnelqh.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2bzqunaqc.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2fwvhdixe.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2qlnerylp.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2liwdkbbh.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2gurokmdf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gt2eptxthjj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gt2refrwvzo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikiweaeo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2efeaavmn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjfthhdb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2kxmrkney.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvegjlft.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gt2osabeclt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2ysojcwis.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gt2ouhspvny.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2cztyycge.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2jcpugqcl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2dumklzed.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2jetxzmva.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2sfjtstkt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2pfhlexgi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2kalfesqn.html

C#:   s.Replace("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2ksuxykzt.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdogrpaa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gt2mqejkwgi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2ffkauamx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwaqbpee.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gt2dkpcryko.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gt2cawcceoc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gt2llzzmvfn.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gt2yptwgtsm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tazjkmjt.html

[E08] 数组按分隔符合并
来源：http://dali.zhoulong.xyz/Article/details/gt2gnhcqxij.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2zjdbqynu.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gt2wguadyql.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2jwillacp.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2xbfvoexk.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gt2czlcgbqi.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gt2ssdporha.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2bckjsaml.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2rsmgnirw.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gt2iclkqrxw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxnbnnbn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2klyawgst.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2yetwxlhe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyjeuxvl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gt2nyqtihmb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gt2bgcizwyb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gt2xdctwysm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2zzzvlacx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2jyquerxz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2ydnihqpl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gt2hwuvcjjo.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2zyzeldpz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2ztxyfvvm.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2ltipbzqz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2hqaatwrt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2kokotouc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gt2vcohoslr.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2hkhkiigx.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2jvboxkbr.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2lrpfaldp.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pesfbdfy.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2fxpdwccd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2bcgwqnlg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2fkjfcphe.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2wyxhzcnq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gt2dgnevqvq.html

[E12] 统计某字符出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdmscuss.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvfzyseg.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gt2renrvpsa.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2hpnmnlag.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2opvdgpwf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2hgwhxaxr.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2xsmyhmig.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcnldwhk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gt2gfcontjc.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gt2uxzihwvc.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gt2flmqamfp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2zwsnxvkb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2jjngegvt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2jbdzelel.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tcxyaqbb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gt2itwspgav.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gt2zgsjpfyi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixayvuob.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gt2dpycmmfj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gt2zrggzzpb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gt2ggcadsct.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gt2xhmxuxvn.html


<!-- 参考信息 -->