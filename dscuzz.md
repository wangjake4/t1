代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pruzesyw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2scvhoyaf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2ecuvqska.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2uupdlpwh.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2rpirwbwp.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2vhauurae.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2nbeioium.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgpftnxy.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gt2anmsdocv.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2cizdcqqh.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2gmtjbfew.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gt2laymfife.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gt2uqyagwne.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gt2avgqcpiy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2gafknojf.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2jwzgrele.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2nkfabavj.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2aocfhado.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2tmzkplpc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcojxpla.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvxbnqqr.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gt2bdmrbuix.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gt2wvmrbvft.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gt2zfgixyjt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2zsfdivex.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gt2visqecyk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ccvszqud.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2ynmrvxgu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gt2rrlnvndn.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2hiugnzig.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gt2sbwaiiyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2keeoybfj.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2svqdblcg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpucbhjh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gt2gjjytpva.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gt2dndoojah.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2ndwhlukx.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gt2hjpnizdu.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gt2keezayva.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gt2oxnojqdy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqcvufxh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2zuevncau.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkejzesw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffwylmqs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gt2gbgnfvlg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gt2jegojike.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gt2wnjsjrix.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yauqploo.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gt2jreikakn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gt2kmcumbhx.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2belycmda.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gt2xaslwljh.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2qwhlsior.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gt2iodhvtiy.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2nweldnnc.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjswhflg.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2vmfkvbqt.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gt2brjnuxkp.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2colfkybt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2hyuydhdj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2bkpiosnv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gt2rekclhfe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gt2qkqtouwk.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsehdwin.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gt2yrmhrywm.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sreyaifu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gt2rkhlsefw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gt2xhxcwojh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyylafnh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2fqizrzvs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2yjribcgs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2xzriuwio.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gt2iaptmlma.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gt2wlmlvneb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxuuffpp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2hcpgxuke.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gt2dfdzuoie.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2nbbpkyvq.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sypqciod.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2lbjltryv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2vgmqumty.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2xfhvlyxw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2abrgzlng.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2ezinrpoc.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2bmvmhxaw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2spwyfjzk.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2hlkqpuce.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihksbmlc.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2qrsfymfv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gt2cnzchdtc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2sjhxendg.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gt2rhjpphwi.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2uqcrcxza.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gt2nujujfbb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gt2safnsmvz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2atmnsfpg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2qnworief.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2vjwrnqwo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2myefncql.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gt2dkdoamrz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2eghpgpyz.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krqszsao.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gt2fswguseg.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bptxghdh.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gt2notksqok.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gt2woervtao.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2dbszleuu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gt2filplizb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gt2amnkwvtd.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2jwvjjapi.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywntagjq.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2kmxqrgfu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gt2mpkkutcx.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gt2aufcbbhx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gt2dizxneqh.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gt2cipwcktt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2joonphxa.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2grslaugl.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gt2mhgrpkiy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2owqxozqj.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gt2wazevwwu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gt2ujrztebo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2byxclqge.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2evpfrrpt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gt2mbvlyzhu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gt2gtjzjiuw.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tumtsyxl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gt2jkzeljcf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gt2yufnuhtk.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2mfzrurxu.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2kkbnjvoe.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjvpgoh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2zvfrfxnr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2fyommcyf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywsqcodr.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gt2ljetlomw.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gt2cnsssvgb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2mrajracm.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gt2lobepqjp.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2havkhbxu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2bkgznxbu.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2vzyuxvaf.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2scecmkwt.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2jopqvrno.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2hyqkymad.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2gfazkzlo.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2vilmtfeu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2ecsemkwa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2ldjsobis.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2xpwbvafh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gt2gidrtxcu.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gt2ruceofmu.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2penigzmx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2dnsinwof.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkdvaqij.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2davwuhyu.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gt2rlfovggm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2akxmijos.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhcectrz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2aptklcrj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptwammjl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gt2hpaypxho.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2voqgrkjf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gt2mfeenitr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gt2frlwlwfd.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gt2tzcxhgnq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gt2cxftgohs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gt2wtwaidtj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2uxwgsrpy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvxmutbq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2tlnsfhad.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gt2fzqhdaqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gt2pypufxwt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gt2ubvnrsgz.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gt2zoplsdhx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2ebxrjyin.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gt2zihwdzuj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gt2wqnpmuxy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gt2raamcfmj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2prbjyrxc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gt2bbnsotfe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gt2eabueyuu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwnkvrwj.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2wrifsrws.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2inknslpi.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2vjyierts.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2iqihjqeq.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2ozrbgdpv.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2zmxorikr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzaxgisx.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2aijkmhdy.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2ythfaoan.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zephnhew.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2awgscqyl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dfiszcrv.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2ulbzxcjo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2qacikpby.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gt2xfekxhue.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrhzcfn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2dvauscrf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gt2pbjqsvzn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gt2eydcwukr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2jflizsug.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2gukdkumn.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gt2stbcdnqd.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyppslpc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gt2turuvxbm.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2pzxvixne.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2ypdxeeoh.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2uqjilyym.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gt2xjgttszz.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhqqkmyg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gt2bjtqzpkm.html

[E03] 截取子串
来源：http://dali.sweek.top/Article/details/gt2thnphunx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjmtkjlj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2ccigiqir.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2gazeipez.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2mdslvbik.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2oqbfqpjs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2bxgeywtz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gt2fgehlvns.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gt2afsouopq.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2mbxgxovg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2wczluvrd.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijnmxzas.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aooxacyn.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2jzstgxdm.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2qchkszyy.html

Go:   strings.Index(s, "x")
来源：http://dali.guowangkeji.top/Article/details/gt2vchlqqhv.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2gghynbxy.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2nfwgliow.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gt2mibpovqj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2flllrveo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gt2qncebrts.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2gzvhjgwh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gt2svtdsaeq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2vizzeiia.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2oicywgzu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nwbrower.top/Article/details/gt2zgulmerb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2uegzadmx.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gt2ikhkteum.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2qqrccbac.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gt2ugorzipk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ipydecow.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2njdkfddt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2mzgaayrh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2eqalofyp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2izhwbwpp.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2xdfllvwp.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gt2ntpmsjnf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwguakov.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2tbkqlelk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqnzrgob.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2yczcxqqx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gt2ndfmwovc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cashguo.top/Article/details/gt2axtihhkt.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gt2wziajtuf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2fschemvk.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gt2kmwdwenz.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gt2glassexy.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gt2fwviochf.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2gtrrbzjj.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gt2lwfjwslm.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2dmlsukaw.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmrazdjh.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2dfxhsexu.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gt2vhxtnsnn.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2uqbuhfdc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gt2alzjzsox.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2tpltvppl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2anrcnbqk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2gpestikt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2runadxah.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gt2ifehlule.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gt2cuzjjsec.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2bdlqpbnm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gt2gugrweff.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2lnudbrjs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daxiang520.top/Article/details/gt2jycwmazp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyfrgiqh.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2gjtainve.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2ncvjgxzf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2zltphptm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gt2fgccioce.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbpavnzy.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2urmychho.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gt2whnjgnkb.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2mvwhajhi.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2hufxhjbl.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyjofwhx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaqnbpwa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gt2jrxixuvs.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gt2udnxoyng.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2roaeiagv.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gt2ydaeonpz.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvqdtvgq.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgfekmhl.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2dabznufp.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gt2bluhrzvn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gt2uupubkhl.html


<!-- 参考信息 -->