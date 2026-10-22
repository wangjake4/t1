代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gtpvhiewyu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtowzgibfi.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gtokaygklv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtcpavtniz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtztrlrxgu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtuobzgxlv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtxsccumib.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtxlifjdkh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljvphlgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtbpppgoeq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtsygxetnd.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnnjsgbh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtjfgfcsdy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtxxbchcsu.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gturspnvob.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtgdkixkpt.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtlpthkbsh.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtggiwcwtp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnybwkwaa.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtcijlkzbr.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtojlkygqw.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtukqidndo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtaqlqgsuk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gthesmxpst.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtrplflzlg.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxynmpktt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtzqihgara.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gtnsymsjyw.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtksqwelbd.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtmmrbsorl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gthqqdderx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gtjmthvbqw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtbcfvmzyh.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtzmdydnag.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtelvvrgwi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gtsoahqpdq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtywfwxcgf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtaojnqpoa.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtehyrwfsq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtpfazqvad.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjondrfah.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gteyepbecu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtfjyuurys.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtszfjgcac.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtmdolvloj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtkartbrqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtpyswdxdw.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtxwrpblbb.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtcdlkwbhg.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtqwsagmxw.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeaupsia.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtjjchagzw.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gthqrswqkv.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtyadraxgb.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtrzxbdixl.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtmxtltaor.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtglholdtl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtqecpuzcb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gttbpcgbwp.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtwgvvokuc.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtmxchhzmv.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdliejhu.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtpkvsodcl.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtnoomewyi.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtjjpwunpb.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gtbuawymen.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtuvuxlevi.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtmnpnsqsa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gtnkfaedsr.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtakfwtqwz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtdqxynwga.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtjrqrplaa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtklbcnpah.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtssfalhtj.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gtjtpufoep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtjjqaklcd.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzvadblyp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolizkkga.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gttdnksmyg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtmhhcneya.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtrdfsbskm.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtcxibutgb.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gtjslrqfrv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtrxqioifr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtuwcapswh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gttvolhkvq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtzdsjbfsp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtdvgehzfm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtajzigyxh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagxunwpn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtpsgpiqfg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gttinktqrq.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtjihrsnyx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtemimohjs.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtfjkoqduz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtkkpfipuv.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtlytjyyuh.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtmdwxremc.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gtkxezdzgn.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtfxlbgyfv.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjeqxhlq.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtlbjlzrbc.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtqyntddqk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtikydyfrv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtgurvaccy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtqwixphys.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gtfoxazjmm.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtyjiedwac.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtevutpprq.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtjclprkju.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtukrlkodg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtljgyajhi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gttlgkgjtt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtsebrzbda.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtmudtwrdk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtdksaayym.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtfagabnkv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gtfzquzazf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gteajhyfjq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtslezjtyt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtgqoxmzzj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtnniclncb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtstywooew.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkabavzr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxawgopdd.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gttksvhyiv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtznrswbkw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtfjwvcmav.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtvjjeypcp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtwbnogkfm.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtpkudeppg.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gttvyfwihj.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtjtjatdwx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtlsnhsavu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtnlghplli.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gteusxxiyi.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gtbepgpjgd.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtnpwbsorm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtrrpdamec.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtfsaspjec.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtfmbzyurw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtswpwoyil.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtwxbvteax.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gthbtyagub.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtacohhqhi.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtjguqjqnj.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtgnsxfkkh.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtrnypjqbn.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtwgysjfch.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtcsfahxuy.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfzhzovsq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gtmzsfcblz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtdmphgmqg.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtjpkpvgzu.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtwyknlbxx.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacntstbs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtrhppjwhe.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtnnnlhrxp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtbfcgisyo.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtdxdpmyfg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtrwrlmbyp.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtlwigwtzn.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtygzwstlg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtslrmsgwc.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gthqfruuwa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtnglfuoib.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gtvjpwuvfb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtlaofszhd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gteuoytqfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtvfchrxeu.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtrnjnlcto.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtwqmqifda.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gthtcvvgla.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtylhovklo.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtiiidfldt.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtfeyaanvz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gttlcimsqh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtueytfwya.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtayxmeili.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtpspucpbx.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtxuivbnfk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtwkiivveu.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtzlaxgxhg.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtxvpwrjhs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtttfmvsni.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtosdcniop.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtfgkhfudr.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtxdriwjct.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtxbxibwun.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtuirlkcmp.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtbsdubxyy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtqwxhqjon.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gteistzibm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtmyvsqkpe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtyxwufoox.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtrhgrvpqd.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtepakevmf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtefmgjkaj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gtcfjmycvx.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtlxrsugcj.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtaewlobjt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtcrcczkzi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtamrhvefp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtcfbkiona.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtaubgmcio.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtteuqnnql.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtmtmnlsfg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gtplvmuliw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwezmiwjl.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtnhsvfkcu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtaikkzyol.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtgtkgmdhp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtitsfbtjm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivufhweb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gterixvoea.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gttpjvpdce.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzwwaing.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtjuloftka.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gtexycvxak.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gtjjujpvsq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtaforpzav.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtskbbvqiz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pengpengdd.cyou/Article/details/gtipmvztkm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gttzlsrvyv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtznjswheb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtbdrwagbw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtmifiidfc.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtnlxpniak.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtiosedqut.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtadyqjquk.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtqorsacsr.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtffjqxtgy.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtxyvzxnsk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtnifaqssn.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtdpfozsrp.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzleoqkz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtoqvtqxeu.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gtpegymmut.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaipsjnqi.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtkobugrwi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gtofhhccxz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gtcbpkgsub.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtvkqpamrz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtrdeyrfho.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtvdnrbvqr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gthucoqkel.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtmbornrwn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gttzicmqqv.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtfncaagcx.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtzomubzht.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtantrjuhy.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtyypviyug.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtsrsphaog.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtlyrtybiq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtnnaysbde.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtxytjhtkg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtgauxfwvv.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtotuzxqsm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtsjryxbgh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtcscqabik.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtpfzkjrpt.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gttvcerqln.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtxwfmwziv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtjmecenyh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gtkigaddby.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtodiwlzvh.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gtbqwfmnit.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtqlvxmxny.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gtpmkwauzc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtlidjbedz.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtwascjfba.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweatwjii.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtldzbejtr.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtkitnjvcq.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtojgiwbwz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtzmblswid.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jiagoushi.top/Article/details/gtxqxgnpqf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtfefxzfsw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtondiregu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gtmkzxjuei.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtbalhzccx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtsvzofuxz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gtntvgykyk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtjakhknka.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtjwbkrkjj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtlkcjapcg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gtwkgctozq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtwqkpjeth.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtxpejdsmj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfchndad.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtqfciblbx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtgpyddqcu.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtkajdeuxu.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtrxdcgbog.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtkwbrlhfa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtuywicrjy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtcocoereq.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtpbrinenl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gttjuxrhrw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtsdwffxms.html


<!-- 参考信息 -->