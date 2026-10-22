代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gt2zybkescp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bwvgjcyu.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2ucjqywrw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gt2mjyyuvnr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2igsvqlml.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2ntkspkyo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkgnengz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gt2keeqxkoi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gt2lwxktsoz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2lrqzlvkk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gt2jwwjecrx.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aftygibd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2asxytbqq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2cxowyswz.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2mkzarsna.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2ufcctiyf.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2kadtovaz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2kolrlbno.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gt2aetickpj.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2syucayxm.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgpnrika.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkmwcwuq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gt2jleyadvu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gt2qkmoxhrh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2tqqkcftq.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gt2yfvtvycs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gt2wlqyhjte.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ieiupvrm.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2mzczlgyf.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2gioysahs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znzjksab.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gt2endhzuiv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2xpdlqjif.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gt2ctjzhtrz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gt2lckkqgvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gt2svjozysq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gt2iylqwddh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gt2guvrcqui.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gt2vhkcmwnm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2jrasysrv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfczlfvq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2phcpfyic.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gt2apvguouo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gt2yxurouky.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2nmsxidot.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pudeakhs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sysojqed.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhiqgpld.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2zbitzlca.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gt2bxybgovt.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2nkytvafg.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gt2qzfmabli.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gt2babjmxgs.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfhizdvn.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2hfdqrvgo.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gt2gxokhhfu.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gt2flnoykxq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gt2hppeytrg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2bsqviosa.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2ajxzfxov.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfljvbvv.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2xhizaqgx.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2bhjimxpx.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2vpopzswu.html

C#:   list.GetRange(1, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2rwdeelsb.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gt2lloqopcd.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gt2uhyfxwxx.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gt2efequsam.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2fwddufvf.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gt2ybunpsqt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2siqnngfp.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2czzlpqgt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2avvealpu.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gt2edxehofj.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gt2bcqkxsnp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebwzznel.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gt2trymytum.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gt2cihxrfai.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2kiakxozq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gt2nbkhibxw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hrjwcrkr.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2tsnblxoo.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gt2wxboghwo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhoulong.xyz/Article/details/gt2lnfwdcdg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hftwyfwb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2zgdzcbxz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpmllvkw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gt2fluqodqm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stotokvr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2qoiihryp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oglirnvx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gt2kslkuxtd.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2ewarkzbj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gt2xnmymxii.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2bnsnjbdn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gt2usxrwtcv.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2cnkshsrp.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gt2tmhoogfe.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2qhqutbtv.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2rmwjwmdw.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2nlbosdsh.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gt2pblizvdj.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2skgbfyds.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2ruegojhm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2shjjxmix.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2uxwwwjml.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gt2jkyoxxob.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2wltnijyw.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gt2nayxokfw.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ottkblea.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gt2ctfhydya.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2dguolyhe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gt2dkmbavwz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2nvrvigdb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqzhiiuq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gt2zyfuyllc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gt2kpmuzmgn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrprltip.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2qotzpxwk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gt2hmeznskt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gt2ichwmxrf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhfrtkrh.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2tccahext.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wruikrdg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drxufavg.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2njmcufmo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2qwfrjdks.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrpdlnz.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gt2oizeozqk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2swjjbmxn.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2feqixyue.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2niimmrzt.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2ydhogims.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2hxfjczkt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gt2lwvlwyxf.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gt2jwgargfn.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gt2nleesske.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gt2ahkwlrmp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2xtusaaay.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gt2rthimwxm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2xswuakaj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2alcoqtih.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2napxcivp.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gt2svkvwksa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2xoamhrij.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gt2hfckjpya.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gt2fidxozcd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oigtkknz.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2qkdqzldv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gt2phncwmig.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gt2ksdawhuz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gt2qacxgwcn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2kmgyyorc.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2vhamgiwb.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2tjraxotg.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2slgdlbmb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2njfezrxt.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gt2ltdehrjd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gt2jjvxoexw.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgamhlwj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gt2ldqyeftq.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gt2qtigczlq.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gt2lmtlowwa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2ooutfrdm.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gt2nrzbywva.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gt2lprxlofy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyokeoup.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idxqfnpn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2sjeazapa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gt2ztmdotfp.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gt2pniejnmp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gt2owfaercm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gt2zdjjmegk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gt2lubfczvd.html

Py:   Counter(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2qxenexdx.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqwkjrrl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2intmhivz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxdlrpm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gt2gvmdhvvn.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gt2frbgvvju.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gt2uxfyhqdd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gt2anrkvbfr.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2emmpveyl.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gt2zrbfmijf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gt2qmjeruvo.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2jwxgcsvp.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2gaurfbqd.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2cmoqnqbj.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2rbuslkds.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2vjjsgmds.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2iojvrxjr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2rpiadfbe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2ugpstkpi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gt2hlnutxoi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fddathgx.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2tkuxgicr.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cinccpti.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2wkzuvngk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2iamcxpnd.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2hychhgum.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gt2avixkqsb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2aguwxenk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gt2hvgcnxub.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2mdhcjjxw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2dyszctxw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gt2qevazgnp.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2aenlqtdq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2waqkexvh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbqmzqqs.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2lsbxnldx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gt2hgpjrwcy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egjlciye.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2teyyxvtz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2cfrnhtjl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gt2sgxcgaun.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gt2ocoucgfh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.0kj1m.cn/Article/details/gt2vsdmdwdv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkgyyfea.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gt2pztghits.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gt2rpoofonn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gt2xfvuioax.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gt2ralebyoz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gt2xevtjinc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2pppefzzs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gt2afitmthm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2sblxogzs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvmdfmxp.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gt2bwceppfm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2bqfjffop.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gghoefpz.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2clkwakpp.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2hbazpcaf.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2nobqfwyx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gt2joqxuqux.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nigadbyr.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2urghomii.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ffvbumjt.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gt2avhxhyct.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ajfspyqk.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfveplsg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gt2erzvoodu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gt2lgrztfpn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2fiilprsc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2geypsxqd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gt2fprreukb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gt2ewmjpjdr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gt2klwjkvfj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2zgoxgkpb.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gt2ftesxvss.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2xkbzezwn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2asniowls.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2whqljvkf.html

TS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2jfccibeg.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2geszvzyd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuxming.cn/Article/details/gt2jmdqgntl.html

Ruby: "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2duuqaqbw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gt2plxihjgz.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2zgqtsptf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2axcxlxkv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sddgtnvh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2ksijbwhh.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2ceunnzsu.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2ukuubgsz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2ynlvmxxb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2mnxzzuvd.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gt2chqkwbit.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gt2ukkhkukz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2uezbusdp.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gt2nwdutgaw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fzhhl.top/Article/details/gt2upzjixox.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2srsqiypc.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2lmbubdmu.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gt2shozthfl.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2qsunvibd.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2utuzaldx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdexnwnk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdcddubh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gt2oetqjunm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2praagacj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gt2tdtltyyz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2eiqiymiz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2wfxncjvh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvaxrcin.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2yfoilyqu.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gt2tneklahd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2osnnwhqn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gt2nykwmuuo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2obghvfic.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2wuwzbpoe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2grjcfywr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2jdiocdtx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2ivxnpdhu.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2kcrjavdn.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gt2cosdbmrf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gt2siwdopsu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2avhsrlas.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gt2pcujbhux.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gt2nxpiclbd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gt2vpmsejct.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gt2obsjsmvf.html


<!-- 参考信息 -->