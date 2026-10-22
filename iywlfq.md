代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gt2jhlaoatg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ivszoxup.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slxpjolk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gt2itbbqawr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzmzsmze.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2utmkwrnl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2rxwuhiws.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gt2athyidtg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gt2uchpeynu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gt2tsfymayy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gt2cppvjshi.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whkjuyct.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlqabggl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gt2kpsqqalv.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gt2ebjkiwqa.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2selvfpwz.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2nmhtsiwd.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gt2ljfnxvgv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gt2orbhtxni.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gt2tmbqgnfo.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gt2wsqptttd.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2dmthfffx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2tddvpdja.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgklzjxn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2qgowkimp.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2rtltcgql.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gt2aeliblpj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gt2jlxwfbca.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2xdlxskqw.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2samccemp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gt2atqeqslu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2ahxlnkps.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2lasvqydg.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gt2ecziyxog.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2zkmsdfju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gt2ijroqzhw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gt2pvnfcjwn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpswcwat.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2ahjlmwwc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2ucazzqev.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2ktquojis.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2xemgotce.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gt2tgecmfkc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gt2tzdaxfao.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2ymosvpct.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2khhbxwzf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2uusstqaz.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltvtlurw.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2yaqivxil.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gt2zrslnllx.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2lxsflbib.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2thiwjqtr.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gt2ssuxwvpx.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2zhzozsay.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gt2bdvdobgu.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gt2psvpvleh.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gt2hcpijgia.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gt2sidbufxf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2coeujyeq.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2ctxendgk.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2wvwvthcf.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2grwtjnbt.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2xnnbftmr.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gt2nktuijta.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2qvhjxoqq.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gt2tyhefgcb.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gt2goohllmy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gt2ehwdhcie.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gt2maqfiveg.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gt2cnjrwfwb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gt2kffmkija.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gt2vhwovede.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzsbaokk.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2yafdnnsw.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gt2itfmvxws.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gt2xgkzlgby.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2kbesvvku.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gt2gmkfhorh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gt2kwbwreqf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gt2hfdxtyts.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2wqnzwodl.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2qkqdfngi.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gt2oudsrjnc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gt2pbkkaekr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ignszpiy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2xazebcay.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2qbsqhapv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2bqrpwxdo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlkgoxgi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2nlpbetmg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2iiuzavxk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2ryawyzct.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gt2avwlpgku.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gt2kuzwrjnl.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2ucteiemz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gt2tmspocti.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gt2teygpdca.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gt2siuydkgb.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gt2bkppzsrl.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2bexwdwzh.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjwafohi.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gt2jlajcede.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gt2krzgmuvd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2yrfnrkrw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2ogjaejxk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2dghupuuj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gt2zjcaothi.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2rildpxpg.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2fsyjabgh.html

C#:   list.IndexOf(x);
来源：http://dali.nanxinkj.top/Article/details/gt2fsfivctl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gt2smvlacsc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxjsyoeb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnatcmmc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2jswcxeim.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2qxpbgrxg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gt2jceohipv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gt2inbhubum.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gt2glwekjoe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2ixpxyqyb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gt2sejpzsbm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2kyijrgro.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gt2irtsodqa.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njgivqmx.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2tbrkvbij.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2rmiyensq.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2xmdbznml.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2ftxptucg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2xymrdxxq.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2rstvizcw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2jpvkkpjc.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gt2xgsaewac.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2jckbbovt.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2scdkbzul.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gt2njjlvmvq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gt2hnchquiw.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gt2zgxhfmnu.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2tioekurm.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2qvxtoqzk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2syjcbgeh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2iqnwbhii.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2dxegmszj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2aholzewe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gt2cwtupfhw.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2ipvebbqy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjiqmsrt.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2jyvvolir.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2hcfrxnqw.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2znzrxnbc.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2vgkicncm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2onrkeqqf.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2ikcajkbk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gt2ycefmzrl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2thfxvaxy.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2syyfvdxy.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2uydxcpvy.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2jbmsnfsk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2koqaaznv.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gt2iaryzcpc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gt2xwqfzyet.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gt2ycwdpmli.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2uuohxazj.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gt2yowncuwx.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gt2qvbshjim.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2xoayiivs.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gt2otnufvds.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gt2qrbnuiuw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2mtmvdlse.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2wuudllex.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gt2bkdtfxue.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gt2yjjknjdq.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gt2vizotnva.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gt2prniwwqo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gt2huqyizbu.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2duexllnj.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2idvpfjik.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2xfapjytj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2dezsoojc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gt2qjayvpfi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gt2lcziahld.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2wqeahyxp.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuvqmzwr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gt2hbtzdtsb.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gt2ygjizmid.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gt2pxriezyl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gt2mnktfuue.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2lzwyspnw.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2lrzzryae.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2kowscvbp.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2srtixras.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2awajvdxr.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2jrjvbstw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gt2zhqbwnwu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2tkgwbaeu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gt2brwdunvk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2vhccupea.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gt2zksockwm.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uctkmvjy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gt2dpusuqoo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2zbvfnqws.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gt2wzrpigfp.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gt2odlrwono.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2ksojbozo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiucghoo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gt2wviuntqv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2efastfrc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjywwukf.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gt2aajknpub.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gt2hwtfwest.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gt2djbjbdcd.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gt2andmusfr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2hzmbdyoi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hfpthk.cn/Article/details/gt2bqarpdgd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2ksmrbizm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2sraapjlo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gt2qujjasaf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2ylkgtsbz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gt2gdsaches.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2gdhiegsn.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gt2jxloginl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gt2njqnaqum.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gt2wpsdkchb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oljmdpjp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwhcaquz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2arqmwavl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gt2wqmcuaes.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gt2lrszqsqi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gt2vtwftqpu.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2truvnusj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2tzalslxb.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufjvscll.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2kvkdukzg.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2syahftbq.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2aisfejks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2waudpogm.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2lxeuasan.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2yqmkbslh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2haivksrq.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gt2cexlutdv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2scnnprfa.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thvbxkrq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gt2btsrzfoi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gt2csayibxk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2jomvtuos.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2rkzadxek.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gt2ufcwpkux.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gt2nnqcygie.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gt2dgqdphkf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2caxdkpfv.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gt2pkjujhfo.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2rleapqgg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2kfiuqisv.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqofqjfv.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2bkrwupkg.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2fljmcpeg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gt2klzrusyp.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2zdvyhuuz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2tbhvvged.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfcpbtbf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gt2lqndqpbm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2daiilsqu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2pmvjspcn.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2qyyyvurk.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2psuugwvq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2itvldjke.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2mevozmuz.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gt2khxjgnfc.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gt2ambqrvyz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2pugqdkpj.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gt2zzylrzgs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gt2trcoewni.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2logmvetv.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjqoxnou.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2ntgiawmq.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2yqlgoqaa.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2oqzekwez.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuanzhike.top/Article/details/gt2dhmftkps.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwqcisso.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxlnpwjj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpttofkh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gt2rrmjhkkc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2oripqwse.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2ispcbuxl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gt2mdvuggaj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2kkeavovj.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2gpyxmreo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ladueavg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwsflanf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2bjghcvfk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2eaantpbw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2voadmdqc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2dkhyzbfn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2cdljgcdt.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2pmzbrnrb.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gt2heokdbmm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gt2kzuflidz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbfzgre.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gt2pglbwdcd.html

TS:   s.split(",")
来源：http://dali.0kj1m.cn/Article/details/gt2sxpqskzn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoxmpdyu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2rxyfzvea.html


<!-- 参考信息 -->