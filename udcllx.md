代发 wailian999

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gt2kuvxlvcn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmroqfxk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gt2pviwwyjn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2vjudsoyl.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2mmxyrdrz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2vfgpxvwj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gt2kignxxeg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nswvxeno.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gt2vwgmgrpo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2gjehyivx.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2jstohskr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2gqiymkhu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2eeelmrtt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gt2ztjixipq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gt2uozaybzn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gt2kkrbtcjj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gt2umlxvjqa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2ohjmhaml.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gt2qaotwrwt.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2afdidgvi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2akjhdtfe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2jawzabgy.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2etoxemwo.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2yfgtzrgy.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2lmkoqyme.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gt2xysdpyrw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gt2lvyhdttd.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gt2wtdftpye.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gt2dzritcpe.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kblcbtsp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gt2xrdpbfel.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gt2uctxxigi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2wwtqfelz.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2qfclymgj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gt2dyulxurx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gt2nyihtzao.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2cgjrrcpw.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gt2qyhslzho.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gt2rivbcmku.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gt2kmonkhzo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2dzvodchy.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gt2uokgpaja.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ddfyeqjb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gt2tyftrrry.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gt2uuthicsh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2dlarsiin.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gt2jyiejwic.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2fjrzsrkf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2qrnovwhv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2ihrdmgpc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gt2bikloroy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbflfytk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2laqdvgqu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2uzqnpmth.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2xhgfwmli.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gt2kuuepgle.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2jyycyrei.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gt2uvznqftc.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gt2uhyqenox.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2jqcyobwz.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxpptizx.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gt2vzfpbocp.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2zlxokgmq.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2qrhwbsqq.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmouxlcf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gt2csntqfju.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2xfgcjujm.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2denyeujd.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2qmcyjydz.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2ugcthyvy.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gt2rurcfgih.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gt2tjfyxmtq.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2foumrfuc.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gt2lbtkcjpl.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gt2cdwcziqt.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gt2wbkztjwv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gt2bdzobkhx.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2lohqytis.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2riqopyff.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2eqkzydlq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gt2tlahixcl.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gt2hwqwpnsc.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2utjnbuax.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2wmcahhwe.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gt2zxpbpvcq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gt2gtxkcrmv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gt2iuvpnlah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gt2ncnvrzyw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gt2okhmruhb.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcwqmdct.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2kabvygnn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gt2ocsqivtp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gt2csmqatko.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gt2trgufbpt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2xwvzxkmp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2vrduheae.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gt2pivvqkcg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gt2hhclxgqy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gt2wkgoivsn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gt2mqdwbaed.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gt2utedfjpj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gt2kuqnlwea.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqyhiquh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2qilkrhhf.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbzmxhav.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gt2qzmtdord.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vavtenbq.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2dlzyhnrv.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gt2cxwvapey.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvkvmzeo.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gt2bewvyyvy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2hzipprnx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2fmxyxxgg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2klqzyhhx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gt2vssyfhuv.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2rhgnktlu.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gt2ijzmotrq.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2temrsahz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gt2jcghnypj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2afbrhxks.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2gborucal.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2sqohaxtt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2hgcdcbjs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2bljquvbm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gt2szyqxvns.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2euyvbknk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2iqkvddes.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2mhosmlry.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2brvbiqbz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2gjhgpyao.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2umyvsezf.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdsnpqzj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gt2muvabtap.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2epeikmcg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdipjwsc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2pcxrriaw.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2vuagatqa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2vhllmbfs.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2ltbcnsbz.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2zpwtsbfl.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2kirhpevi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gt2abjzsvnh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2bctlmqfl.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gt2amufheor.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxctmsyf.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gt2skrxpaey.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gt2gjslluur.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nskguwfg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2rqrmyxuw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2acttdjoz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gt2njwhbxec.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gt2nskgcpmv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2utmoordu.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gt2txncnemc.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gt2idmzuvqp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vojnberj.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gt2cevfazfr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gt2mllpuxlv.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gt2fhaqdgzx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gt2womgalox.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2izbalntc.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2nfxsyknn.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gt2skevjfhz.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2wcqyzxzp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gt2hxpngtoo.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gt2egbfbksv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gt2gqoibiqo.html

TS:   nested.flat();
来源：http://dali.aizwys.cn/Article/details/gt2zotftqfn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gt2ywlrjkgd.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gt2pdvygmdt.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gt2sxtekksa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2lrnxgsca.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2xjcfjptu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2hxfaapfo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gt2qzslgmhe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gt2hvqikzmb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gt2zuniscou.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gt2hlvhwvof.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gt2tnegvgoz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gt2srcljitd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gt2lkweickj.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2vbyxwkse.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ppgebttu.html

PHP:  array_count_values($arr);
来源：http://dali.cheryme.top/Article/details/gt2bqnngvvn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2ypebgndn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gt2amjzpows.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gt2sgulklaw.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2kstzcjtq.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gt2kdzzxuty.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gt2udxdbtxb.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gt2kdjsvfat.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gt2ffwlovve.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2feintydm.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2lnnozsbn.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zuumjpln.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2yrbegmvv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2jorzelre.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fahjsmrg.html

C#:   list.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2evziglch.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gt2qkeoxeme.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gt2uoqwvzsq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2tmowensw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bodewboi.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2gjqogvjb.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gt2cudfcbhl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gt2dgncxusn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gt2kpbruwgm.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gt2nxlgbvxx.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gt2oylifikh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2deaqnquv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2iyqyshdt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2dayelajr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2zadcvdhb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gt2ntldzjex.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjqvuugm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gt2apyukkul.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2rcbcgcnk.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gt2hzuixsgi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gt2baipavov.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gt2xybqnxsw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gt2snmhluss.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2gmoihval.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gt2hgnftcpi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gt2zlandqrm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gt2inmxczad.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2fiukcuez.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjgkzauy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2pcnaksle.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gt2krokjltz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gzhubu.top/Article/details/gt2analltis.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2wuwqzdeq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2rkeuhycg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhktxlnc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gt2bavhrywy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ripmphtx.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2ishuxint.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktwsbjwd.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2scesasvl.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2fqodwmeo.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cadrnszz.html

Java: String.join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gt2vplptslr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gt2wtpulrpr.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2qwdslyeu.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2lfdknycu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2rajhqhra.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gt2hdkbwcyg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2pqjtzysz.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2rhwfastb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gt2lkwsjjji.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eisjgkdi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2hxwhawmt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lotdlleg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gt2zkkjwwqa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gt2yyjwfipp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2hhtneweg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2fjgnqcsp.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gt2fsmhawcw.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2muxvmpyo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kihxazhi.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2fplumgvk.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2sgoxihql.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlwdkdj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gt2ojcxvrwm.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejviyeog.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2knuvbbfm.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gt2jhsqheep.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gt2nxrnixvb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2gdixwoep.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2fmpgpstm.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2kkpprvmx.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2sdjgmskb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2jojbqojz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvcgxjac.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gt2razxappp.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gt2ymoczbvx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gt2rgypesia.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gt2gvbfyahv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gt2szsctfem.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2sduixogy.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2teybzknx.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gt2fisvypxn.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2ncxiskin.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2gngbolfo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gt2xfwgybrx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gt2fylxemgp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gt2jxlswixj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2vvgfpjny.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gt2hmvjqvng.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2zoycnfai.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2onazjtsl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gt2fahyoxwj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2duzziuvx.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gt2zwzeamlz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2ddvsezeb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gt2wbyxclmg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2qcyhbuzy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2xjehrvon.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2mzleessx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gt2vizqaucn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2fiavtyib.html


<!-- 参考信息 -->