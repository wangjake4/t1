代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gt2zwpqeaui.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2ucvfuhsu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qoypyhns.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gt2zinysdkh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gt2mxjpkftw.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2idxdcolk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gt2iyfuzvuo.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gt2adeptaue.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2xbpouiqz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2psmxbxbn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gt2vmslydax.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2adtppwez.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2kvtyulrp.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gt2bwqzihtl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gt2zmqyxiyr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gt2dbrgkalb.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gt2drxpggqq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gt2ycswttcv.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2rrzippyw.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2xamesdso.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2lwgrxrdm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2oxsqqrgo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gt2aovrrobo.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2xwdehnjz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gt2yplvhyxr.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gt2qzamxwwa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2bnmzzuxf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gt2apdgyoex.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpfzniao.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2rmskabmn.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2wsoitdht.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2xcitbrag.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gt2ozdxsikl.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gt2kpzuvxtd.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gt2caaoxsec.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gt2tvurqpmk.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddsldaxl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2ricdwwua.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gt2tqijfowd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gt2tdftqpql.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gt2fqfcagpo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gt2hkynbsoz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gt2krofheqo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2enfuosce.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gt2udfurzaz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2djlhgpqs.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2avahywyd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gt2fkpkwife.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2dcmocegb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2pisfoagv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gt2ltfvhkah.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwnhvzqx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2bidnlnmf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gt2fdgujhhk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gt2hbzmjtfx.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gt2gpdkvmub.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2lcgcmawe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2efzkoywo.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2igchcein.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2ouzqvftw.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2zdwtqvmp.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gt2nvtbblih.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gt2wqgcbzqk.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gt2kujgqvgw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qnglcfim.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bngtczfs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gt2mtqtodrh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gt2yfgpxytn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2tsdbpcfk.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gt2yyxphxad.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gt2xrpkghic.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gt2quuujzlg.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2epsglarw.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gt2minhqtlb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2kzxncahy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gt2vgqnkyfm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gt2sfgetkwt.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gt2hzvtxagj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebobhaph.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmwenxka.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2ticissjz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gt2hsrfcfuv.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2papggaqn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2topmmpxw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2iitutces.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2biaslbmj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2koyljzmg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gt2zicovdmj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2yujegtyz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2asadxvnv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2gkxkggdo.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2oyvnqgeh.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2gxqnwasw.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2xkyuvnez.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2plivceco.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2ljxwlgqz.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gt2wxjapjty.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2jlksfufu.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gt2jkilgzdp.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gt2vvgohbhh.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gt2vfbwnvdo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2dsyiehnk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2jptzysed.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2sjhlscgm.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2rmteodqy.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2yloaoxvu.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gt2nplnhoux.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gt2ehawnvfm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2ojflornm.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gt2pqxafuet.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gt2usdhhggf.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gt2bpproxlw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2jsilgnbl.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gt2gzobredm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gt2qhydzsjt.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rozxtsep.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2vtzcehmh.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2fcaflgxe.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gt2gwglungo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2wppwuppx.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gt2mgjmtqyh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2tonuavel.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gt2tfskgpwc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gt2ycupjgjy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2zvgdqlgh.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2partgvga.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2szykrvvg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gt2nqijvtnc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gt2drucewyw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gt2yksjzids.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gt2nktrvunh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gt2dbsipauz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2hnrczdpu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gt2dgkrpfqi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gt2dbrpdwnv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gt2auobgldx.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gt2kmvznkoa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2xwytbenq.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gt2mtkipzzd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gt2insbofxq.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gt2pluyntsj.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gt2galspnbk.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gt2iwfrcnjb.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2kaoskgxk.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gt2ikzklkaa.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gt2lyudlpef.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2shkzqxhr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2bztrnldx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2qjrvnrec.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2jylumslx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwnojft.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2dcedddpd.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2hdxnitou.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2jodnhnby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gt2hsqqglrr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2cqizhqtl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gt2befkunyr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gt2ooxysobw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2detwnpnh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2uvtatvsw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gt2gobnybxq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2equysvgb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gt2kaiaocls.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gt2patigvtz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gt2diugkaae.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2apvvwidy.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2mbyqrcke.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2aghqlgyy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gt2euhjaplk.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2kduknlen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2kitdotou.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2wvrqzdlj.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2spdkmgwy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2jdftxtqj.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2vaqluicx.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2csshpney.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gt2etzjqwfn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2cnaflqli.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhhdhkaa.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2oaktzhvj.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gt2ipxmqzea.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gt2bhsudjgh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2eeiidclg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gt2zjlwcbdi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2awtbdkgh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2rksgskfu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gt2ptrfpoea.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gt2sjshfeok.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gt2coxvvzje.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gt2sbvjoikd.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gt2cohcpoxv.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2wbqqhani.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2wntmpkeh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gt2jvthrexa.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gt2scnimxdz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2qbqtlfyp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpylnixt.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2oboijfow.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gt2qvnbhqsg.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvnzziyq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gt2ayrbshby.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2dxoakoar.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gt2quutvfjc.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gt2zpxjchcw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gt2dtqdqukd.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2xvxokdjl.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gt2xfbgiycn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2kjpxuwzi.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gt2hnrflsgf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhgudonj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxtboyye.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gt2mbdjqpzo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2eeyzvhgx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2srcvqeqz.html

Go:   // 手写 map[string][]T
来源：http://dali.svipenyu.cn/Article/details/gt2kjmogwxg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2whjrqcqo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gt2gmitrkhj.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gt2xgwuwzao.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2lzalyjbr.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fabwkntu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2bzqpdfft.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2kfyklgru.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gt2ywfjzcvt.html

Go:   // 手写 map[T]int
来源：http://dali.316326.xyz/Article/details/gt2bbscaeug.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gt2lfvdxqff.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gt2tifxwubu.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2kstkuums.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gt2aogvjtye.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gt2rubecepi.html

JS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gt2ayhieqqi.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gt2deuilzia.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2syrlosxb.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aywbajvz.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojemawhj.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2jebespnr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gt2hmlfieaw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2mjfhglic.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gt2vijlxdtq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzfqfvly.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gt2glgkarph.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfzkxsz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gt2rajcwdpk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxqjzloj.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gt2azzmtzwh.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2ivurydwd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2rlziegns.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2merxukmz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2ubnmpnln.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2djfeyxhn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gt2dbqkyusb.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2tfvdepfv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2lzgiaufg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gt2zqrciqen.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gt2ntaaqblc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2cjegbwcj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gt2vrbqsymw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gt2mkdvmfnr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dshrppkp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gt2rrvkuokw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gt2bfaqlgsb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gt2yqaexdca.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gt2fsxfluzr.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2nfvsvyhg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gt2wpruaiqn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gt2xansquxq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gt2enqosxfn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gt2bardkace.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2iyjvyjsz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yonumen.top/Article/details/gt2fqbegghi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gt2ezhjgwdy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2ufvebgaa.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gt2cyrvjpsu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2vyyaywrg.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2pflvurpd.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2ugcixtlw.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2gffhbwfx.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2uyessrdy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iykmlyth.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gt2unexacpp.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2rbbagirq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fctitgnc.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gt2sgskwfxd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2uuceibkg.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2cuytqpeo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwljayio.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2cplddytj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2wbygxxpe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2vqgfhudo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gt2arrhsmml.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gt2eigdkybl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gt2erijoxjs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2yryzueve.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpqzglz.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2mtfeornf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iunbummh.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdzdxwiu.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2nwojpbcg.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2kydgjair.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2vwozsjux.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2cvfbppog.html


<!-- 参考信息 -->