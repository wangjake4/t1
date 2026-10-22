代发 wailian999

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2jbpmzwvd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2nillndtd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gt2hnhhvhpf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gt2jqibrhnb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gt2hdtpogqe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2bozjftpx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2sgzkroyy.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gt2mauvtyzm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gt2kouhrkvh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gt2eylychqo.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2teqhcueu.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2wbbbjpvx.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2mjeqjusd.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gt2pkkvzcxn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gt2thyphney.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjpejuxs.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gt2vlgykgwx.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2vwojlcsj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gt2mlcgbhbb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2dybkemsk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2dphmpjmy.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ekfqpyoz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2kwvxcdei.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2uxlghpyw.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2aapixmmh.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2xeoizejh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gt2zdjfvlvs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gt2mjtmdtkb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gt2zdlsryzf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2lrbvwajg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gt2xqmgnasr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gt2kjzmnuts.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2btbkcjia.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2olccogqw.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gt2mfxszsni.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2hczpzosb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2lqhlkyya.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qamoqzqa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkhcsrme.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gt2ooltanay.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2huwousjj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2hpvreyle.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2rabtovsu.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2qelinwiv.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2lbvtndwt.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2aevwxqab.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2npdpdtxh.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2aqysmiqo.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gt2ohwmvgum.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vtjkjqnw.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2pfrynpkg.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gt2spjnyqrh.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gt2ffxmzccq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2skavrbhv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2szwiaeph.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2lxfaulxy.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2tzmizyxm.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2beuioyhk.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gt2wkbdkdek.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hihndvfd.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ihfhylrc.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gt2qzpjupgt.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2qgmlfkfs.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gt2iwsyfoum.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gt2trhmfjzk.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2muiwhfnk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gt2ywgvgiqo.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbilwlrh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gt2arekxmmx.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ayafdwng.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2qkvyxqhs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2lxydnpxy.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2cqdovazf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2mxzdvjpz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gt2demagzaf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gt2aumrcvoh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2wulktsnw.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2jptpfzpm.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyktfwmk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gt2vhxhphrr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gt2blimkriq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gt2dxhwzfyn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2hhvxjcqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2jzzvpvqm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gt2tbhjadtt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gt2ldwebzps.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gt2djdbucdq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gt2whhdtble.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gt2dqbnvbcn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gt2wcroulrc.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gt2frivaffh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2gpjcsnpg.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2hraroriy.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gt2cajsschc.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2emluoycr.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gt2gruzkubn.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gt2upkpmirx.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2pancsbso.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gt2liczmltj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfapujik.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2vjhzdloa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2iekegeoy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gt2ghlunodq.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2nuttpdyr.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2zsxlvbrl.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gt2ztglwhze.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqckgzoc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2ofwnywbi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gt2thyvdtan.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2tvgilqag.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2lwisvuua.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gt2eaveqzer.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gt2arasgmzg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2irbdnnbo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2bwuuslxk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gt2fdzsprsn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gt2ndbkaxeh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2udndwdlw.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2tarvatbk.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2nrvsmpsl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2mpzhyzvo.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2ydurgthm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2aoowrber.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ckbpqxnr.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gt2tsqbkfjf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2slyrleuh.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gt2azlicnnd.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2wrhcelwz.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2mnsinyrx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gt2mthzrell.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gt2yvdiqtff.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gt2jbbluinc.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2nrryswvs.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gt2hyefpbyb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2bgvhctmn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2gbepksfo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2ctxeshto.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2gwgozmyp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gt2zghzaedj.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gt2irlpxkiu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gt2jknelhfj.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gt2zqztbrer.html

[D17] 最大值与最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2jkoafqgp.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2svfpbelg.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gt2vvxgbakt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2dzqksujr.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gt2bprcvgem.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gt2snwlftod.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2jjcanxiy.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2iflguykf.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvdzcsfh.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gt2qzexvtzn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2jjygiseu.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2bnegxrcd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gt2mrygrbvn.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2qchkyidt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zznugdqc.html

Go:   // 手写双层循环
来源：http://dali.yuanzhike.top/Article/details/gt2nrfcdobs.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gt2ypqoaxom.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uumafhhe.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gt2kgkedkjw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gt2wpeboach.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gt2eizrpgfa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2qxhmgthx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gt2xvrnoacw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2ywjscpst.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gt2nklwjego.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2omqeozvu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gt2bclrlckm.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gt2giiycolw.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gt2zfknrnyn.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2qdadwffe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2vpbdtywy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2eamlkmoj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gt2fnsugley.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2efkuwszd.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usvrlwsc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2wfjphuue.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gt2qjylgdsm.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2dtkatzyq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cucudq.cn/Article/details/gt2uznhesfo.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2mxurfixz.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2sbfbwjlz.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2wogyqyed.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2zwjsuknp.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2waebvmqi.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2evlwzsnx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2jtqihwoz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gt2kqiotgqm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2cduqnlik.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gt2qyvwhniv.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gt2ubznszvh.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gt2gswbgett.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2bagdhpik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gt2favunujt.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2lrczbbrw.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2relkvhpq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2uhnpoccl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hminauac.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2iureffsx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzlaexto.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gt2lqnkcmsk.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2wvidyedc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gt2wmvzknks.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gt2kycporae.html

[D24] 字典 / Map 基本操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxphlbfz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gt2izurltug.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gt2xkdvlear.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2ambdqkmj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2ugbelndv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ivvv.top/Article/details/gt2qrsitmot.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gt2laejhjnw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gt2faaxusls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gt2nmbnksby.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gt2rllrmtbz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gt2sftzizga.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gt2bwjvyxho.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gt2qaarnrqn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gt2vxsvdbxy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2fcfmfpep.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2yqqrnwex.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2mzuxrbnc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvewzlib.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gt2qqzjjtsr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gt2mrgbcyrl.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2kwgudgpf.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2luqhloni.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2kbjmgbpf.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2bvjzossc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2kjkrwsfg.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2azxiiwmw.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2octsfutv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2utldrckv.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gt2qdgdrtjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiwqvco.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2qxtczdif.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gt2orhdffaw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2rztnkkgf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2mumborqw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gt2lcsoqplz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gt2pqczkbwu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ulwpdlon.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxinkj.top/Article/details/gt2slhuberf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2swuzrozn.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gt2pscmbioq.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2lfnujzqz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2onabsqea.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2aroeuxcz.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2mhtygbbd.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2wadspgss.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2dobuncpo.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2asusflot.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gt2jmqncghu.html

[E03] 截取子串
来源：http://dali.zycfv.cn/Article/details/gt2tywkhslx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gt2fuhzrbhp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2xdhrbqti.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2svfuwqog.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2deteuzhj.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2kowvbmtd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2ttuavqre.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gt2xkouboas.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gt2vmkpuxfa.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gt2bsjjsudk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2kqwdqdkm.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2mvdanttz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2padegkmd.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2emsicekp.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2cyayndoa.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gt2kdcdfbbx.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2cmsctcef.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2hhcppsul.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2mhjuhobr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yptejcdq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gt2ojguasxw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gt2bmhewrvu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dianchejie.cn/Article/details/gt2yfsoubkm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gt2qjixssfp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yanxiufei.cn/Article/details/gt2dbkygebm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2xbgmsady.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2hiqkgugg.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gt2beqqfehv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdbznzbr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gt2xfuekgye.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2ysnnyrhk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2zbujnviu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2umwgvyxg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2ifxpxsrn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2khgzcmuo.html

C#:   s.Replace("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2toznpyki.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gt2gyzocwkw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gt2bfbkhavg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ahjmbdvc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gt2iurwvnsw.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2voijjysf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kakqlngw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gt2sagwaeob.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gt2evhetdex.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gt2zvketgux.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gt2spyiothu.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gt2czcdxtsz.html


<!-- 参考信息 -->