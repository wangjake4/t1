代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbqufxy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gt2wbbufamo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2objueztf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlltmmwo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gt2knoiujbm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nstrohda.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2alexeocw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gt2gvkgtgtq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gt2oqmgmeqy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvzwjpfm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2jkhzojkp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nurghiyf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2ifmzdhvi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzsxanbq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gt2yhkolvsp.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gt2nghfkscz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gt2dsqxazmy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gt2pzumzsqi.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2bvzpkurx.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2kyijbuvz.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2fgvlmjqf.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lspnvmuu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gt2ucuvckut.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gt2dwooycih.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gt2bdymmxos.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2jofgqnao.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gt2xecuhhfl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozrgmnxh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2afvqgomm.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2zznohumg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oicdasfy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gt2xxbsystm.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2wzozjmbe.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2cfkqeiwg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gt2wnqhdswl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxvpkdw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2esynbyoq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2zusrvbpw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwbkfdoh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gt2caacmbrq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gt2avqjuctx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gt2ouaefgik.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gt2zczfnruk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2jyyogppl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2pfndlhbv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzfkptkz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gt2mebetsoy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2mbccmwey.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2ccqdrfku.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2xkizxcit.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2rzrdvvgw.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2hrzfrdes.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2tqjjhmaw.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2zwgefseh.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2lscjbipf.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbvvpidh.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gt2pajgwllb.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2jgmfqfmx.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2ubgwpixo.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gt2pufdnvuc.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gt2ounvyadg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gt2yqdhcmnv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2vjiylkuh.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2ywyaavyd.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2nvfynqaz.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2gudxpngq.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2ekdueloj.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2xuencqfj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2vxjvoixq.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atvkench.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2pnvxjzyb.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gt2oqvggqsw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2mxtddtlv.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gt2suuftfdr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2lyokqmoq.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gt2bbqtqmat.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gt2wswkpwiv.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gt2rjvbkxdi.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqnhcwpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2yrqnfosr.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gt2bbissefo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gt2nzfiwlzq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gt2rxxmezdj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fncwqnze.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2mamztace.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2dyfofcby.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gt2vlxzorrp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gt2capnnujk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gt2yhytcuyg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gt2zczsxygc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gt2lppuwxhu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2ssihrnce.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gt2ojuyhbsr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gt2xgmfrtsj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2siaizzfd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2watgunwg.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gt2gziindnw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gt2ledbcgxn.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2gifbdzor.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2itisauyg.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gt2wwefpnas.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gt2zznhqebw.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2gmgedoyy.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2vzxtitue.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2xjwzpuzs.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gt2bhavgwsx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2ysxztgrn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2slpvnxnj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2sqphuydt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gt2yzoffgpl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gt2soyxjdev.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2jzmrmurp.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2epqpdrcx.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2fdhfejkk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gt2dfuibstr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2qlklryex.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gt2iqwfeulw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2ypukwlsm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2untzxzfp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2uxifjquu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gt2mzurdwpy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2xxjwrlwp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2lzcfwwco.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2ibnutpba.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsakcday.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gt2lyvqhtkw.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2wsqsoces.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2germvwju.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gt2krpfobzy.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2vctqhimc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gt2tmesekke.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynoyvdnw.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtxejkbj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2pipqneww.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2hyhzlztw.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ailbmlff.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2btaoojgt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gt2ulduumwv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gt2ixswkhhp.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gt2wphktzut.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmechgbq.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2keabnwbq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2clhaaycw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2qpxbvovj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gt2azuztrcr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2cbmszlmo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gt2bqozdvmy.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gt2tlkuytkk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gt2kvghxkmk.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryabysoe.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gt2xacgwmcu.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gt2blmkvkac.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gknsoxsj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gt2bhkmqjmq.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gt2atopdqnc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gt2dtkbgdcs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2vjvfbcia.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gt2wjihglfv.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlbxtwwg.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gt2oovpfuhw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gt2dygpqinp.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gt2ydcoefun.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gt2endnewru.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gt2shypxdke.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gt2kzvlhmbj.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2yuuojius.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxkeqmu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2xflmtxhc.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gt2lcfwcddg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2xnnknzew.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2frmewwmp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gt2tbaqgcby.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhmuiido.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gt2eokmnbwr.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2taxtjlvf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gt2djqswvel.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2xitpnvmz.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2pljfelhs.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2jsjcaumv.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gt2wvisdcxl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymxnszhz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2xvzvzwfi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gt2gdznukmw.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gt2oliqmwvf.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyusrnlt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gt2spbvzdaj.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gt2gzxtjmmv.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2jglinnjo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgnbqwza.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2cysdgabd.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2olmcixwa.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2zqdzhtki.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwtgjuoh.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maxrbdyy.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2jgedjobj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gt2ezijldnr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2gjkotfty.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2ejhpifje.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gt2rqudzjqh.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gt2vawlhjhu.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgamhkvt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gt2ikhjinol.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2wesxyylt.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2smlpzdry.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gt2ujmttooz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2lenwsuyh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gt2zxobmguj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzbmlsud.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxqdwffa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gt2znhpxzbl.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gt2zowrdpmw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mliwafsp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gt2rjkfbunw.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gt2eodqadke.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gt2nbstdxxx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2rnztpadu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2ipaceieq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlypmgdj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gt2kmgcgvgn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gt2qhvrjats.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gt2vqdupocc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2qctoamxk.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gt2xfigfewt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gt2exrjmbzk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbacuhug.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gt2naqzcuyb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksqfxeck.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gt2emqyjtrw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gt2rzhnpisn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gt2egakjolf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2ndquncme.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gt2mfntafcg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gt2tnogyxuw.html

PHP:  implode(", ", $arr);
来源：http://dali.meibo888.top/Article/details/gt2ozojvwcx.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2kcmgbpgs.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2mtpvvtwm.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2aelbqdpo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2fxzewtse.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2jczsyceq.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gt2bxmdmowd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2trwxklrv.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gt2vpkazuxq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2acshsxsk.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2vkgvtcfl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2yunzzudc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gt2fhofjdho.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zougoown.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2dkefcijn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2puuduscw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gt2ozlfzyky.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2tzjrmgkp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2almfagwo.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2fmjebfqi.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2azewdzco.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2mfdbvhvm.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2fnsohhmm.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2nlyknasr.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdmfkjae.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2hcqbnonw.html

Ruby: "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2ocwbcblf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2cwibfsuo.html

[E03] 截取子串
来源：http://dali.zycfv.cn/Article/details/gt2icgimdjp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gt2nehqczpd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2fsrpquku.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2qdrzezkn.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2dpltxkcv.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2xlhgikbi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2ihymijkd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2kswuexrn.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gt2crmnjeau.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2qdpeyewp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2oemggzap.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gt2htwydpkg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gt2yryibqft.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2fqclvxzo.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2lzklqlpa.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gt2jysogrvp.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2mmymivof.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2htrhmnrz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2rjwftqci.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gt2dmksurzf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gt2lqkytpoq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2atmzybqg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2pafptggs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2wymlapce.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gt2yxmwwlka.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gt2uumawfrw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2lnoscnto.html

[E06] 替换子串
来源：http://dali.aizwys.cn/Article/details/gt2tidsrxbp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gt2bdglhwtt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gt2lbfncziw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2viygxfvt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2nwqjajee.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2brkzxags.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2comajzgf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2apcyjmbc.html

C#:   s.Replace("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2mrylpyea.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gt2rhgxblvq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyqgkou.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2ueeeryjw.html


<!-- 参考信息 -->