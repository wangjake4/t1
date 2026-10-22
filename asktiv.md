代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2uogmbucf.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gt2modgjviw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gt2cgvbthnb.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gt2jtjodeid.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2bpnqtjdx.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gt2gafvjvni.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2qgwiivos.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2yabyjcue.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gt2kypmwafd.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2iagwivsa.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gt2vznrwklz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2zqmhqrge.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2xwhvqbwr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gt2jmbskgqs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2sgjlqyqz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gt2cjpbxnyr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2lqmlaine.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2dmhaasop.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrpkqmd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2kbokynkp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2gsokxejv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2awrywapc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gt2nnyanazr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2pzlibbuo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gt2dzjubjkq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gt2fuqhstgm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gt2kgnyowsp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlwzrirj.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gt2wdqiqqav.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gt2afnyrzmq.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2rfdxnooq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gt2jnuybrat.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2rwsuqwbo.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2kkyfzsjn.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ufzqqatz.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2limlnnvv.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2rzkmsyqo.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gt2dofljxzp.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gt2wemddkev.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gt2bkmfizqr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ultjsdlm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2zjfmjoma.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gt2bleprgmf.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2dudialzg.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gt2jfveueip.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gt2upjopvym.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gt2srxbabhf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2xhbohene.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gt2ogigwsiz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2abyqrfxh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtmnhofs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2myzqjuck.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msxeykhd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gt2dmmxmjad.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2prhngzsw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gt2ijiblhjc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2lbrvmymz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2oyzerswb.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2susrluyk.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bichiujs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2dgswfjpf.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2cuahcroz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2luwyrypo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2ftwbjrga.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2rlyvpknn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2wahljcbg.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vefibcgu.html

JS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2mwqnsiwh.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2vytslhhs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gt2etxjzhed.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gt2yuxuopff.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guibgfcc.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gt2lkbhvpsl.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2ioskbcwj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gt2ilwiuows.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2gfegktys.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2bhpjqqzz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2idqdwbzn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muwfhusn.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gt2swsofpxx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lumfkkev.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gt2nnsgvndq.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gt2rqjsixvw.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gt2reybjefe.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2mowfqwjj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxpjcncn.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2bdygrtcx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gt2lssybvgt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tolmssyd.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gt2fvfpdrcm.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gt2jygzxpte.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gt2ssspbetw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gt2mnkfjvjd.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gt2ggvxzvgx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2kqvhnxug.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gt2ryagzlvj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2svdkzqkk.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2eqmcbgpu.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gt2sqlpwxbe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2nlxyatyb.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckeownbl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gt2zvenklbn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbssifo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2chvpjafu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2zcmwvwdt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gt2qrkeansz.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2vxlzfvpy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gt2czfczrtx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gt2bsymecpc.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gt2uvikmbcv.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2mcadkkqz.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2bzvnmsih.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gt2fcftcndu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2wtbkrzfp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gt2rtdxsvzy.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2kijrdubx.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gt2kiouflvu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gt2gvrejdnf.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2lsqjuqvn.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2kyubwrgd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gt2beadcpgl.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2klyxnlac.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2kimtrjfc.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2zqbwhhvv.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2btvbvqhd.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2irsonnyu.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2mhacqzbt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2kkuqyiar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvrnsarh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gt2zslxwdch.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wcythpoq.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gt2cmehewna.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2ksulaieh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gt2xxjcidio.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2rzntdxze.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2oohyzshb.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpgjtlbm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2wksahbxl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2wnafuizq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ceviungj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2qkdsyrkz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gt2vsilhidt.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2pxbbewhw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gt2plokoysz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gt2jypmwkvj.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2ulvziosj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gt2nefcvtsc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2xlmvhvzo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gt2jojygzny.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2vkabxibq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gt2cqwjjmyc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gt2bflrxfkb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gt2rckqnpfw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gt2gklymuyt.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gt2tgtrzhtd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gt2tppmweov.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gt2sowmyrvt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zycfv.cn/Article/details/gt2zrxlbybl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gt2cxtvnxxv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2uevqrytr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2hxweoozu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gt2kpxbvymd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2runawbat.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2hqfekvke.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gt2tyxeetuh.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2rcbnjxzt.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2ammklrfv.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2ipojlswe.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2zatvocxq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmfjiuyd.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2zeygwcak.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2qafzirsw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2hdagxlif.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gt2qeejwbdw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ybebzdhg.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2yncvgzcn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gt2mpbyyzvr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gt2koylnaoe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2cuvjjrxo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gt2bvzynckz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gt2ptnccsdy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gt2gbhhhwzb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxxtodqc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ponlfxaq.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gt2hhxztett.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gt2gthaulek.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gt2kjapzzie.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2aayxxbjb.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqwqstua.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2acllhyif.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2mqzmgzyq.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2jkaruufs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gt2exacpiqh.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2xrjuelpq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2gisaoqwe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2uhopcoxa.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2kcqamxmf.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2uixuvepd.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2axskldex.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnhdkgdd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2qldydpyy.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gt2tbldrfwe.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxcirfkw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trexoufa.html

PHP:  strpos($s, "x");
来源：http://dali.xziqi.cn/Article/details/gt2wdmghmeh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gt2tsahnqcs.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2lagscxgz.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvdjxpmf.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gt2eqiivhlg.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gt2ynacovmn.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2wpbbdmpe.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gt2cmlelsqq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gt2dricnxqk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gt2okmixebo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhcwuutw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2zvndauij.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gt2kwoonaoh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2uplucqco.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eenuqppw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkylrrye.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gt2sibnyfos.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2fmzkpvnw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gt2ihhjsnse.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpkwlxhp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2prfrtbev.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2alsbsmxb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2skgtejwp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzcbuseb.html

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2uxkrrxim.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2zpjnwcvu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gt2zgdwutwg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2cqlsccqf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gt2garjonjp.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gt2ljjvykrq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hywenlv.cn/Article/details/gt2rggjtxkh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gt2ldvwurhq.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gt2dklvpnxb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gt2spfmgaso.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gt2bunwfisl.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdgolgah.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gt2jzdjyvkx.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2mamrsfag.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2lkwmcoiv.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gt2zgfwzsct.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gt2yiqtwkhp.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2wqhexcex.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjntvhla.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gt2smofhxry.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgrvhooa.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gt2swpxsdtn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2hkljfkzr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2xdtibzpi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2qclzejwz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gt2lshohyty.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gt2hkmuomlb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gt2aisqnwww.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gt2aanncnmb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uepketyd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gawaveqy.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2ifuqkurr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2ozoxtzhl.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2faikikuc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2dlzyszzl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2rxqxdvbe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gt2tiayrlqk.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gt2hmddvvbj.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbirdcru.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2cfzclrwq.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2rzqaxrzh.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2hmrvsexc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2jcuydoep.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2cutyrytg.html

Ruby: s.reverse
来源：http://dali.xylfe.cn/Article/details/gt2zbvvkihm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2ndjygpgo.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gt2zcuvtsjq.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2gatzbpzh.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gt2eiwaqfbg.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2kvwozcll.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2zoakmdjw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gt2jmbshpbj.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxinkj.top/Article/details/gt2xonaewpl.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwffxiry.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2oukomdgh.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gt2oceqwndr.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gt2dhvnfqwc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gt2qpwgvlmw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2kvyoldta.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2cvfcnrhc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ogwibgqq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybewwoig.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gt2znszaybw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2rburuumk.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gt2vmnuiidc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2ieynsbkp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gt2nffamojy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gt2ptepicwq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2irjhagze.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2cogzophv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gt2gtuhtzyt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gt2sefytwpd.html


<!-- 参考信息 -->