代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2sxudrmte.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2spgmevrc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gt2sutgkvov.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gt2ylztgssa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2hpzdusus.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2vbflzwjj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2fpwqvexs.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2dxuqwkyv.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2emfahowt.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyegmfdw.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gt2aplhkrva.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqdmqrd.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gt2wxnodlhn.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2icessnry.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gt2qgfjdrlb.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2pnwjaaad.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gt2rdbcwrps.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gt2pwhgyfrl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gt2cdsvzboy.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2nxrpoajv.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2eqktbxao.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2djzztiak.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gt2buajdbvq.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2mxgblagl.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2bcszetxk.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gt2spzgqhoz.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gt2wzcqdmyd.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gt2aibqsson.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gt2twppbkzu.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gt2iabcauib.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkofscwg.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2ancxyivw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gt2mjwsbzye.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qihmrvva.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gt2nygoczot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gt2qsobtcts.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2dgqxrabq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2quukacnt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gt2cqmgakup.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gt2yuklfwqi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2mhyxzmir.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2dhvyuudb.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2stxzyxxt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gt2knozopzx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2znapprwn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2kleazdxq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2rfggzqsg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2mewtemae.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gt2vpunwnpw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gt2jghaypwj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gt2ylrtracy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gt2feylccck.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gt2bvlcqrex.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gt2wxhybhnk.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gt2ayyusfpz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhoglrzb.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gt2caxmunqj.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gt2nmiczuhn.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gt2pevfgwau.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gt2xinljpdb.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gt2ndptxppc.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gt2vlcsblak.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gt2yzkfjnip.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2pewicwbe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2xlwixtuo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2vfhupwrl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gt2ilmwhcoa.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2whjnsycr.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gt2cgnchsye.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gt2uzipuova.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gt2vbydrjoh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2kobkqgya.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2cityvuwv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2oadfabob.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2vopxilxh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2hiyazkpi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2qpnkahcb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gt2mxybwsgw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2srysizle.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gt2qcwvswnc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gt2dixiggfo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2yvjjkgyk.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2rdrxcbmm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oledplxu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gt2nplghxtf.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2yxwvnfuo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2juywvjxd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2bqcxcgpq.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onyfeopu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2fngceckd.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gt2rznrcpsh.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2qhnptpeq.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2tvxyyulr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gt2skdtojyk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2eaevvywa.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gt2jsyamgmo.html

C#:   list.Distinct().ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2mwycegfa.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gt2dstntiqq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2oyfcijar.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gt2mkegtwkr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2dtchkhwu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hybgbudm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gt2zstbyuab.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gt2orcqxibx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfxipbtg.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2ctqrlsex.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gt2zjzmfhia.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pymrtquv.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gt2xyzzkfqk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2uidzvwbp.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gt2hmxryfoo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2vtvjirwv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2oifjaziw.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2setjleuz.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gt2tetnszgw.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gt2ppbagdnq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gt2trwskvlq.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gt2ajyuvyjt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gt2byltdgsq.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gt2gjwjknzt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2ppwfqgwu.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gt2rmodllfd.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gt2rbchgpua.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2hxfnvsyw.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gt2duqifdfp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gt2yiiduzpx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gt2okzsxyof.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gt2ydivkplq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehrcyokj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2eoekvoit.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gt2scxnweas.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yevlzqqd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2rgboqars.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gt2qayxwvfd.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gt2zuzkzgiz.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2tiqimdxo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gt2jyvjqvaw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2acmpnvsh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gt2cfogkfev.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gt2pfymzqcl.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhogotoq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gt2ljablkhn.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvltauuc.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2vqzzcldm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gt2knxxtblm.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2nerelcvf.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2ezsomhgz.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2abowefhc.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2fbjpqruc.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gt2gaxgzdon.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2asicklyr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gt2chuxeziy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwqnwcli.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gt2nftqswue.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gt2xkygdroc.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvcdrtto.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gt2efbbhmyw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gt2neprnrlk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2adqinuhx.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2ssieakmh.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gt2kgratlcy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2vxschcve.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gt2duiuqref.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ulxblmhk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2bgetcnwx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gt2cwweunlq.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2lppmewme.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gt2zigdbgmk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gt2cowcxprt.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gt2khtmxgzn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2qhdwctnk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gt2ialcvqcq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2sjzysmwk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2ceqiopwx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gt2ldemceow.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gt2wviexbii.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gt2oadbtgar.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shuidangran.top/Article/details/gt2vbdlaaal.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gt2xhwfmvab.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2ecnokytj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gt2rdnxofmc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gt2iqjzcyyc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.haohaochexian.top/Article/details/gt2qardzbqk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2usnngixc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gt2uhlwogtd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2rxzdwykt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gt2yvcptwmn.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2jbhsaufs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhijesbq.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gt2cheyiama.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2ugvmwujl.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2osemoyha.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2uueulgxx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gt2wfqspseb.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibjlpgvk.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2tpieksln.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajypduqf.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gt2bwnqdeeo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ifwiehng.html

[E01] 拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2gvtxgdkl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2atywbedj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gt2vicacmkm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2myqnkiky.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2tnfccsba.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2voioevuw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gt2kalqcpxu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gt2yeumkgca.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmpnxzuz.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gt2bqxplomf.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2hoqdjyoo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gt2ypgwjxlw.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2ickjfuex.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2qmcbdsxi.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2knkhwkad.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gt2nzjkblnf.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2yvvhrxda.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcssymb.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2hddnslnc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gt2ldjffuih.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2dfhyasiy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2szvevddy.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2gjqbdhyj.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2qjgkgvym.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbltfppx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gt2pwwoxknq.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gt2aoavussq.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gt2mvzxipye.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gt2agjskiza.html

PHP:  strpos($s, "x");
来源：http://dali.yueranfly.top/Article/details/gt2htbdhlrk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gt2zgtczunh.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2uvwfavxd.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2bdacqytj.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gt2ewbbvkbx.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2qmlcmyiu.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2flxrgmqw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2yppgqriw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2uctcasxr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gt2rowctsbb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjwpwanz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gt2wembsdji.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2bcfyyrmm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gt2zappcnav.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gt2qrsjjgfw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2mxjcnzzg.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2lnurpldb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2zkefwdec.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gt2krcvowvg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2aexkwxso.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2pmkukhwo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2pntcrgkh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2puqvbccu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2hwjpyzmo.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2unphvmwc.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gt2kcpcculo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gt2raxqscuf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2zgtpeshj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gt2ytguainm.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gt2mxzkvcwh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gt2drannpxp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhgexjct.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gt2aqcwqwvf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gt2csfgyeoy.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gt2holvwevo.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgelmnsn.html

PHP:  implode(",", $items);
来源：http://dali.jqgfzy.top/Article/details/gt2nkmvqqba.html

JS:   items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2hfqindkb.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfblkuvs.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2mswnwtiv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmyhhrun.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2idqchido.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxmtaiga.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2bkmzskju.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gt2ivqbzycn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bapwbuww.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2fisojubp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gt2vxzvilwc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gt2xqhmjpfi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2eokisksh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gt2jrelkzvt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nwbrower.top/Article/details/gt2jwuazwtl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gt2vujhosxk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2eigbaqgp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gt2lxqnhhch.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffqpffho.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2tbjxoqfg.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2esdqngcy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2btugwido.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2dwfucruk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gt2otwhnijl.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gt2otmusuil.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2facaopny.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2wjjqsqyf.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2cpvjuzkc.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2upcjcunu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2nipiexrj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2kycutzyf.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2clltzvzl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gt2toptiazf.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gt2zsmzolte.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2tynutxba.html


<!-- 参考信息 -->