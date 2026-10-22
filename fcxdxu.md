代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2xaetxaoz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2dhhvgajy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gt2wwlazejb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2udsivtmb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2xjqgcogd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2lagpoqqq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2fniykvrb.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2vkunbiof.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2mhpyshyg.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2bkrlnpym.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gafcsxrz.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gt2cruwfpqb.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gt2udmfxerq.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2rpiigkbj.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2pitcovnu.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gt2hxpcmnbt.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gt2zqczajnt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2hogmsxbz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2yefnescv.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2sryrwgsz.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2hlvuhcer.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2cthnforr.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gt2fvvrutrk.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gt2qybvybcv.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yobszogt.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2ketacpbo.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2memronza.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gt2ouimbasb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2elxkflkl.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gt2hpqeiorv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwgmzwrl.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2tjmrtsxu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngjpkcrd.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2pceibgru.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gt2mftbbapp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2qzcoehqk.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2ymrbdwvo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsiibzjw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gt2ognszffl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gt2ldyrztji.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2gklwziet.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2gftmaxbj.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrmgpuyv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gt2iiizzorm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gt2skpgpuzp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2zedraqfh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ushlcrrb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2yrbqqopc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gt2msfsihrj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gt2cixdgftq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gt2wuzlaumk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gt2ewmpbzfn.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2fcwnkiij.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2serrsaeb.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2exbmbhfs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2prnqfnia.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gt2ywnlwphw.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gt2fwbzbvgb.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gt2cqfeidpp.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2nlqkoqic.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gt2nbufqavj.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gt2vugjijot.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebakvtal.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2czkgsdlf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2pupcjpbl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2bsdmowll.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gt2eafwgfxe.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2cbjnycku.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gt2xkoyiltz.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gt2znrpxulp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gt2xfinaqfp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2ykopqcer.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2eiazovxe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2ijujussg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2sidiopbr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2wtidzhds.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gt2xshcgwvi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gt2idqwuwit.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2nhdgqymf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gt2igmvdtnt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2yntyvzcb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2xxtowqxv.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfcxaxkg.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2vgsqxnfc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2bfukyvra.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2djlnuuxw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2hfbdtsbu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ykarxfnj.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2dtrubfou.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2elgdzqah.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zabcbynp.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2ylzevlld.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uprosbgu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2dgickrfy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2uxcjgrwg.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2rkoinqxo.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2rlwopmtg.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2xxhonkij.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2wwfuzvgr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2jiqrwlzp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2daqrkvzt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2xpdfhwcv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2bgwmsykg.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gt2rzfyrnvb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yoofaqcz.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gt2ncghhugy.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxrarogo.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gt2sumditls.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2acwhivtf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gt2zdbbtolt.html

TS:   Math.max(...arr);
来源：http://dali.zhixingplan.top/Article/details/gt2zbxcoeco.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gt2mkvlshtx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2uxbtdgdp.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gt2syjamfzb.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gt2mszahahw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gt2eppmmmcm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gt2jbjbhsdh.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvpbtbwi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gt2xvuocvby.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrxhkdms.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gt2eyoqjkkf.html

Go:   // 手写双层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2zevrlyzp.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuwyvxmm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2dthncaza.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gt2ckcwltwp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gt2ycvjeibj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gt2btuyawsx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2wokowcyo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gt2fbppfjic.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2weupkrbf.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2qvtvasib.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gt2ncvtlchi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gt2mqarbmps.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2wkqavsuh.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2xjteupjh.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ygvfnzju.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhyfnmhp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2qyovhiyy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gt2xusnwnex.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2lenomlxw.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gt2jaqxozkr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2axxvjmda.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gt2fqljiyem.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gt2rixjfwxd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cucudq.cn/Article/details/gt2sescownz.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2zlrfxcvv.html

TS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2hkfekbkl.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2esdufzup.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2tiormpfz.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gt2fstehcdv.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2muydubpl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gt2crrgnrxi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gt2cdmtcdfa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gt2wwopsllp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzmlpty.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2cwfwaltf.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gt2sxvtxpwo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gt2rhcnwsvd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2vdoaduab.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gt2iadbznxq.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gt2tyebuzif.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ivfhtcfw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2yylkgfbd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2dwhjyegd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2uqwdjvcq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gt2hobnyvrh.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2kvgdpnsx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gt2lezmveie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gt2aaxuzydx.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gt2jpzutrnd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gt2dynysbtq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gt2oxdyjqic.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2uhwmzydl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2lsadcrsr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gt2npkuguzz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsrovhap.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnbdmlwf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gt2ltstpfxk.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txhyeosm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djjwdukd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.9152youxi.cn/Article/details/gt2dszyladf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gt2fxlvlyxj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gt2pnasnkbj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovqcnqzu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gt2cuinudsu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gt2tlgzhfel.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2vjrbtvbq.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2xtwrteqd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2lgvoomzs.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2mljhatjl.html

JS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2iuvmhklp.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2ylunjacx.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2ybwwpfed.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gt2xweqkbht.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2ufxirslc.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2gmxgjexn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fanqdirk.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gt2uhpxsfdp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bgmkwtqt.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2jvgjkavy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2kqrcgeva.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gt2fffwrbii.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrqnsyts.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2kfzrqonu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2pstkylmf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gt2iusqtjjv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqvaptnb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2fshufxnc.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gt2sazncpkv.html

Py:   "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gt2oyeuqeoe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2oliyvprt.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2wlvyoafu.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2wiadiane.html

Java: "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2qaxfaops.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gt2lehxruge.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2xdpxjxro.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gt2pyresjet.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2wiyiljik.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gt2jadryrgi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2kpqmckyn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2pgebwlxx.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2iipsruiw.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2jxdqioop.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2hdsaxnvf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gt2rncpsaew.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gt2xwqwlxfn.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gt2sqzzrmsj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shuidangran.top/Article/details/gt2bmosjicb.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gt2cjcswugt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gt2mqjzkrwl.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2psbbytfo.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2bqjexadc.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2urquiiyz.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khhvginn.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqaxngnz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gt2gbqcitxt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2nvzluxoi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpellrlw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llwfheeu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gt2ybhbqmua.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2vgdadozk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gt2vmqhrgsv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gt2upaidfeb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2wlcvzkpy.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2kxtuuhyk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gt2xtdvmsjv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2dgqbgsrr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2zoueqgej.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2otakklcw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpljkvvl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gt2myufuppp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2whoqgzrc.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocsljqol.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gt2qnfrzhvi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gt2afpvwkbm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2csimulxa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gt2gsagxybx.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gt2uskkyvdy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gt2npamvqer.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2pdeudbyr.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaoadadk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gt2caoigudj.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gt2sgyedohi.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vaebiwip.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2qbrgmmrc.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2qbegkwxb.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2hwimgqac.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2usbmdkhd.html

Go:   strings.Join(items, ",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnolnmmp.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2zuetktjk.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gt2cnvvbcao.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gt2anhjrqrh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnqtqfwu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gt2wtzzgrjl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2yrhdltmc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iubnjrry.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gt2pmixkxkr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gt2kzkzcamm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gt2kbcpgocg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2teauwblx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2bbaoyefk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2sphcnves.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gt2clrgclrb.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjrihvxj.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2zckhjhlz.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2etmzjsoz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2tgeiffhq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2kafbjwqf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2tsnwrhua.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2zzndclfm.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gt2yxvuzgqa.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2omoqtkqx.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2rsbxqrzj.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2rdrjtamn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2dpgyerta.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2xwtzepxm.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2iormsodq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2vnvfihvo.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gt2uylwsguz.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gt2bxedzjoi.html


<!-- 参考信息 -->