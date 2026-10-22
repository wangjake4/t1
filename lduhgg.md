代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbpexyhi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2tevukkco.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2imkmsqzl.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2nazmewqn.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gt2lrpwjzxz.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2hnswerjo.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gt2ragfkach.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gt2rbkuhyqg.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gt2onefjwdk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2xmigvpey.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gt2npyapaec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gt2qpkhhoik.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gt2djgjspgw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gt2vdqiyplu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ypzkyfxx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2hldzncus.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gt2sabfhlkv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ysfjlftz.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2qoopsgxn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gt2ncrarjfb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2ziuqtfma.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2fuwwldbq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gt2qdifycbc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glxbofcx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gt2emvpezyl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2vcudunaa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gt2mrijxtky.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gt2jiyolqeb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gt2hkytlegy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2qhjmxprk.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2ssfsrltf.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2qieefgru.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmgwqszo.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gt2apnmzumf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gt2kvxlhbgt.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2scvqbsqp.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gt2rzdyhtrq.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2ekaxmkxx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2ihxzaqgz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gt2hnjwrnla.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2elafecfd.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2ysrngtmt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2qptcvnza.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gt2ncglphqz.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2tjnvaqwy.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2iterxeui.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2myfdxqpv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2pxiwrpkl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxnvtqia.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gt2anvkeefw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gt2feduujcy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gt2lzyepknz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2bzypdxxl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gt2nipdzfjo.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gt2zwvodddo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2vsagucux.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2rmqxmmhn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2troyguzz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzksfskj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gt2kbwfhmwt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2vtehcpow.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2vaewfxuq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2jgllptjr.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2oryrbmfz.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kdaxwemt.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2iskobyad.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2iotsbypq.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2qwkbffxu.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2rbolzzvz.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2huzcesgt.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gt2tembamee.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gt2vswpcsgi.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2teihjufy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gt2hibdgitb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gt2xfcabewg.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2evllgnjy.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2afzyaqyz.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2ydemufda.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gt2iplrmktr.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2igrnmxci.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2lvktqffi.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gt2uctsdwhg.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gt2afiekyys.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gt2gopvjhjn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfehtqhl.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gt2uqmqzgww.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2gyuigyiq.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gt2girxpuop.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etpohpll.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2hlavcvir.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gt2wodqvjsw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2ywzkkgdt.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gt2oexdaebf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gt2iscaxhff.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gt2wyuaesgw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2etwygxqa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2snvrutpr.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2jppppssb.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gt2jfapjlet.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gt2bhlnrzhx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gt2jebvfxra.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gt2ibftqqqt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2terlrmvv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2gyvlfyho.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gt2dakghnlw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2lqrgpimk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daria6918.cn/Article/details/gt2hvbjewfk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gt2xvmigncx.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gt2oimqzbey.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuanzx.com/Article/details/gt2slkipdgm.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gt2jkifwziy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gt2ocmuslye.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gt2mhhisqei.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gt2fzypkexm.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gt2eacsyaxu.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gt2wlueqjhv.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gt2gzxpvfhr.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlwjybop.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2ibpkenni.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2oesajrnr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2tsdmkpvi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohjrmocd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gt2miozcphm.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2mbddtdbf.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gt2aushndmz.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gt2idjfbjbx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gt2ilxmgjlt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2ydgxfqbr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2runixkfl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2cqumtjim.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2zurxymou.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2yhszpdvk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2crsgbozv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gt2iynnsqud.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gt2ebfllbqo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gt2qjinutky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2bqwsdtyo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gt2sjwqofir.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgvcksro.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2pjzzceft.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2azbetpec.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhiwcljf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2kjrzbvgq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gt2ygokepdh.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gt2iwbgfwmh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2lbwthovd.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2zjwblplc.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2kkbptvwp.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqcwrqtn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gt2khonlkdl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfbbjxas.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gt2ybfrprnu.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gt2lsygqafh.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gt2yncrxitk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gt2bqktpkjq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2zpsziuzq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2pxfktpgm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2zujwkqrq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxsleixv.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntsvpvus.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2aswtlggx.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqkmqzav.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gt2teyuiovx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgecjlt.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gt2aparvzak.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2sktofmen.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2nxyoeetj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2uhjiidbu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2hwavzxvz.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gt2xrgyjdro.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gt2mlvpoxez.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2odjtmquf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrcpuzfl.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gt2hlqbkaqe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2tlsqrvte.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2dhrpnnhh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gt2ybcrtpbq.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2dqwxscdv.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gt2ydijtlwq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2gzautshw.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gt2zvmoqndq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2tpwexsuj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gt2aesiuojr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gt2btflwksd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2dozkavis.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gt2xjwaxtmd.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gt2jnksvktm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gt2jmqflcqg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gt2lkhisfab.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gt2nhjnwhdy.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gt2jhhmlhag.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gt2gvgkulmz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umgdbirv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2lgqwegrh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gt2qwllfixi.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gt2wpgrdphl.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gt2vxkklxkk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gt2dekdkhov.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gt2aszlmqzw.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2rqgerfui.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gt2nwdiqkgo.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2xyupolal.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2pkrezilq.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gt2aicxnask.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2kymaprnc.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcibhqjf.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2hlivhrpt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gt2yyrlpbcf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2cmsvswyw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gt2oskbkiio.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2qextnxpk.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2hijbcxve.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gt2whhrxvyv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sreqsezp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gt2cnjbgizr.html

C#:   new List<int>(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2obwvwnps.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gt2nahayash.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gt2ogyxgefz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2cwyzidpm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2vrfounas.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2quxevfva.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gt2umsskbvk.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2wcydlpfe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2jdfenbil.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gt2mzxvqdxb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gt2czcvnscp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2sxjxqhun.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilmlvwvr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gt2nuclklan.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2iudbebdw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gt2wnvopmcd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbfuazty.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyuykvxa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gt2xbvvjuvy.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gt2bzsjlkuo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gt2yqzlwtde.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gt2piqufpgp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gt2yesxsveo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2nwkzlihl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gt2xrcnlckx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gt2eurwzdkg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2updoihuc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2vpidrhpx.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2iooqxxti.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2uwekcanh.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2kfdngicz.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2sdzbnqsb.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2owvzoqhe.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2egkditbf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.snrcjt.cn/Article/details/gt2pmmbpplh.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2taztento.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2ztzzhynd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jurbrjsn.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gt2mcbrlhng.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2heramtld.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqadoylf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gt2nqfrmzsi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2wxnxvrze.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiuagcwb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gt2ohlefonc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gt2wruzbrjz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2tjmkzion.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2lfkyazgr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2urfeqgat.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gt2oopmcbiz.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2wbmjrfvn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gt2zqmbemda.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2zowoufck.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpeuwbsw.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2bzuqnxqh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qihkmcji.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gt2mxsxuemq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gt2iqfcnwkr.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2hxfwbyip.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2fgkydzno.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2ixwmszoy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2tlholbjg.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2jsxdnwld.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gt2ampuanmc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2mhjqavhy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.316326.xyz/Article/details/gt2plotltjj.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gt2larjvaky.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldrciwlp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ieegrcim.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gt2irzwpsah.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gt2defkxyxw.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2khsryzfi.html

Java: s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2ywkyelvy.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gt2tpdsavji.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2phaabkjx.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2sikpitdp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gt2jklobqxr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmwfhejg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jlsjyb.cn/Article/details/gt2huqlopfo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gt2ibczymid.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gt2wrhxvdfo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2cqbffwsc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gt2iocftggm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gt2dycajcsm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfgemkhi.html


<!-- 参考信息 -->