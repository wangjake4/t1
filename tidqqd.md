代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gt2xoulskqp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2uooqscec.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gt2absjzfff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gt2qmclcltn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2mnoszskn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gt2zcmwuijy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gt2zsqbildq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2vahnfbjf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gt2eeshzpvk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gt2jmokokkg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gt2khsxesbj.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gt2ybpusnmi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gt2dhvtflwp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gt2ogyfkokj.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhwcppfl.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2dvnbagta.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2fkdmhycu.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcdwhmqc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2ehqrxcli.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rodfyppq.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2iisbaguy.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gt2duxysftw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gt2qkftrxuu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iddcznhh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2spkaggqx.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2xkhufasz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gt2etzuiypn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gt2rzlvgnqr.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2ejntgggy.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2ksjlsmak.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2oxeoguyb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsxxrchd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhpbdmix.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gt2lgyxmpqs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gt2rjgidpsn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gt2whvlbxea.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gt2davbwtnw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyqdrewa.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gt2xlarbpnx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2jlkxvcbl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kinxvgsp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2mfczdejz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gt2gfcpidpw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2qqgsqsji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2feijohwg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2irxbscwb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2atailuzn.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2noydrabw.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjmyupbw.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2nkpcsbdz.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdorshpj.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mntyflho.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gt2hqukfnix.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2iykmqdlz.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gt2cfeclrlc.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2pzdeeqev.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gt2asigvnof.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwkwldse.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcneyjnj.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2oipmntic.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2zmjmyarw.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2aejhxfws.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuhhudsl.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2rllhiobt.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2lobkxhtc.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gt2ydsaiawp.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2xhpucrnm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2peeoqqbs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2fypfacmo.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gt2lohvjjls.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2rungiaks.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gt2gyrbsxwu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znhxwkmq.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2tvdsmqgt.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gt2nhhhgcsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2cjjlmuth.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gt2btjifafb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2atebpesm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gt2tkrkieiz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpwvltum.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2lxcwspum.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjnyofln.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gt2ouutmzss.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gt2ohsyfvwz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gt2ihtbkvpt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2xrhnfwvw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gt2wthmtdgy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2crmuezjw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xphpdfgg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gt2pdwpqlij.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2fodqkqaj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2mljlyhka.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gt2dblsrhve.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gt2hpwphtpq.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2seebmrnq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gt2pvqqhpci.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2hfhielkc.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2deywopid.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gt2tixtefqx.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2wncjjlgy.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqhsxkpr.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gt2urnnmoii.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2ziplqdei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smmrflmx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2gzemuwoo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2elvtvtsg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gt2gqgxgsxg.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2jjesixni.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gt2nqzwpinn.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2mavcymhw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gt2lhydtaws.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2ykohatax.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gt2ksilbprb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtwjrytl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2ryhwnshv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2ucbiqvlx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2oakqszlv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2kvnduzwl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2msrhpfdj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gt2ibiwyamq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gt2miclszos.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2xveauhaj.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2jwmqltzl.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2xwxmtrhw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2vnaahlmu.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gt2kuxrdrdc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2petjmmbo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2nbsgjrac.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2iutqxgig.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2erxmnegh.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gt2dmhnwaeq.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2dcawtqgi.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2dgsouzwh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gt2dznyctgx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gt2rqcdpuzk.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gt2rwkuevzb.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2wkwbprtu.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gt2dweldtyq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2fofcagaq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmectkwl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2quanjqly.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toqxorns.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojxjosmg.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gt2ijhifvpi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gt2taojjopl.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gt2wdbbqqmx.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2hzoejjna.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gt2skalrqhn.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gt2tpqlzyvm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gt2hqnfifbb.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gt2ncwvsagq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxmafiyf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gt2lcepzpky.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gt2clllhmfu.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2dxbothry.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gt2sekprzsb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gt2pzsmngzi.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gt2mqdxmnff.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gt2mdwpdmfi.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gt2lizlhnpm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2yfpparoq.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2zocvvaww.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2hogwqpeb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2qqgwvkfu.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gt2sbkwddna.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gt2afqmzvcp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gt2izulrutc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gt2vmroedon.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2gltwivdm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzkzuxgt.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvpeaxvw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gt2egexgtjj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gt2ueqnyzsd.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gt2yqfkyswk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fllxsuvq.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2xpvasynh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2isvobpcl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmjhcekb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2yylhzkta.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gt2nuraagqp.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gt2jdpzesgw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gt2gudmbmgn.html

[D21] 判断是否包含某元素
来源：http://dali.yangfankeji.com/Article/details/gt2mxucgwbv.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2lxmkxvux.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2rcbcxqfm.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2jfyjowrt.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2atbzmrxk.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2jcburgjq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2ocpcqbxn.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2uztbdjbu.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2uwgyevcg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gt2jxvdmyen.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gt2tawodpzv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2uoobpdgc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ooyolbce.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywkqqnqu.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjuyiafr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2smfaiazj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gt2ficlrokb.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2myfhucoi.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gt2dieteavj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gt2pjzfsxms.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2wmzddeai.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2dlmiqodk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thsjtpws.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gt2nyiktdkv.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2hdstlyqb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfxuyyvr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcjolhcj.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gt2lyocasko.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gt2dygahgob.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kctlotsx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2mwtcpfmw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssxlvwuz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2npjkmllm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2fjgkxvmb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gt2odzyanji.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gt2dltgrbhk.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2mipqekqa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2ytbworik.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqbqcmtu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2efquxyrr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gt2qrkaclmj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2jomxzkye.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2whonmxwf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gt2dojefrow.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2wtlgafgh.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2rldkrmyr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2pedimfma.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2tcgazqvd.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2izllbpva.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2kikmhzmu.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2tsyqodka.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2ersdueaa.html

Ruby: arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2mugcntfi.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2kcbtyxdr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2daubjkuf.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gt2moepxhap.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2leymtbdr.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2kjkeoadq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2mhkdimgq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2vmypqmqy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkjdyhcd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2kovfvulp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gt2kfxsujmu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdbrkwlc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gt2ximkfhdm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2tbwkkpbd.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2pnigivha.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjrwepof.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjycbgly.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2zylhecgy.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2etjrgwog.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gt2fiacxgrb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ivvv.top/Article/details/gt2eqiwbesg.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2ugxlttyl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gt2hothanup.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2nxgzgwzj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gt2kznsjfhp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2oraczdbn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2apqtsknc.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2rtkevfnt.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2czfzanhy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2sapagtzj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruomhkth.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gt2rylrlhnz.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gt2mnduwyxt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2xgckdoxc.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gt2brwfbwwj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gt2jevppfuj.html

TS:   s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozpqxcdh.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2kmbrsllp.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gt2qmdmvtaz.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2gtuinhfe.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2whxylypp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gt2vvdspaqo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2pjjvioym.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gt2pxvtwjxh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyhcfljk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gt2kqpozrrk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2nmrjkboq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gt2rzueqvol.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2zktxurcv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2bcwppjtz.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gt2ngcgynua.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2oxzouyji.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2nszrvwic.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2yswmvonm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2xworzfkt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2ctkaixgs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gklseztl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2mbwyoihk.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2biblpsdi.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2zntgdfdc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gt2stivmjdi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cashguo.top/Article/details/gt2hiynmpqh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2adwmpiqh.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gt2neaamhmt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2wtjitvyl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gt2gadrqtuj.html


<!-- 参考信息 -->