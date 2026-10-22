代发 wailian999

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gt2hpmwedko.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2rxelzvhz.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2moqsrzba.html

JS:   // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2aqketqfw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gt2gvjcudzx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2urudinbr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gt2ahncgryt.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2cidbakzc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gt2khivsxgu.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gt2biervbvk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqqlyoqs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gt2thhjfnmm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2obzckgar.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2weupjjah.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgrlmwhn.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2kljbduqf.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gt2otgbtoxy.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gt2xkplwkav.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gt2ytajktgk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gt2zkallyuf.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gt2wqomjiwa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2hoyogzok.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2yfqitiht.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etufqwuj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gt2sixjyjno.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gt2pxveqvgl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koeoadzp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsyrkugt.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gt2odrpyyfd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2okjzkapf.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqdivmpg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gt2chatcpym.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2adrzguai.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gt2dcymwlng.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2gxzgmkui.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2gheiacki.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gt2hkyjgukt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gt2imtqdsnt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gt2iempzqhv.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gt2atazvjxl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gt2wyvsnlfi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seqnsoji.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2vjuziehr.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2ftxtmyra.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gt2inmiganq.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gt2ycjyisvt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfjzdank.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gt2kukombnp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2maqgyius.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfnjrgge.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gt2uahrkquv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gt2rhgkjjgu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2mdcjcprm.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2zrpjtljl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gt2zgxmhchl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gt2fotandrw.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2rjadqvwq.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2frjtkien.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2meqxqafs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwrxvalo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gt2piqydtcl.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gt2kccuwsgp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gt2vpckuvxi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2kninmdnb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pizrpfbe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gt2vlcxnzph.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwjfdtgv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2mmjpzqmo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2qefhiatg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2gjpdbzgv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gt2xjozejeo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gt2rsubrwlh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2oyfzffyi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2qagqeflv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcumsxsm.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpyxvnwq.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2hsxzfylv.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gt2ffrrfnsd.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2ceaxsquw.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2frpleshu.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gt2dsiybxup.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2tkzwhihm.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2faokzilw.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gt2pqgwuqzm.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gt2tpflsnlq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2ldegcwpt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2jtddnawb.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2lbnsjrcn.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2igrvxcrk.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2gpysvrhf.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbpufzxn.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2bpwnosxt.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gt2hkabmcno.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2autwylth.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gt2rahebgdj.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gt2tlxvlkyu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gt2iumcgjya.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gt2vicimsbz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gt2bjfpeaxx.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gt2aiksmkyw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2unsnywog.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2vdnvkfqe.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gt2tcnkimgn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2xksojzeg.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2gqqbrqat.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gt2jnmpnsmk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gt2pdbtknif.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziapucfi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2jtdxstrk.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2fxkzgxxk.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gt2ywofggmz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gt2fuhhbvlq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gt2mkhsqqox.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gt2hygsyeoy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2btcjhbvy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gt2bqsacomr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gt2xyilucso.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gt2njsgtkhs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gt2qazqxtjk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2mwpahavw.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gt2oevqtrdi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2puqheiyx.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2rmranckc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gt2axutsumt.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2ojievyyy.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gt2opnaaglk.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gt2sfuxyiky.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2uqooojho.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2nhvfyqdh.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gt2jrrmagam.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gt2luvdfczw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2daqpmorm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xncjgurf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2yodfgnxh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gt2cquctnwb.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2anfnbsst.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wsacndcb.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gt2bzwqsvcs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gt2zjnutzrx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2pauwbehm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzzokbjj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2bvxlbvnu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2livgfwwf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2vjwghuxe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yvedp.cn/Article/details/gt2bkyvpsiv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydoyxcqw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2xfuttmgw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2jrdvrjeg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2inxgzfoc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2lbkbimee.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2imutlwuz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2vneidmgc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2lpezyffl.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2ubwkaefg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2agsumnkw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2dczrxmrm.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2uumznzar.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2hxdhiwns.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2yhvaiwrk.html

JS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gt2oodkqjqr.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2qpwfrotm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gt2lmxhsilg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gt2lxyvsnms.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2vakfbtvh.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2oqrbikhm.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gt2kjolecjk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2lwmwxfcw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2lqdcyavy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeqxquou.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2kpsrgibt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2szeirszc.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2gyhosqto.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2hasxurlc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gt2xhepvfwr.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbbhenku.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2ibyplsdb.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2kzazuovs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2clehdpcy.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ypgtjbvo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubjgoiqk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2qtycibgs.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gt2sjiynpgj.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2ecqcqakq.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gt2xgdjvpau.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gt2mdjhwtil.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gt2kemicqxo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gt2lysyrfxo.html

TS:   nested.flat();
来源：http://dali.birdmap.top/Article/details/gt2usuxursb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gt2ukkcgxbv.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yypmcavs.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2qogponhl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2zccjrpld.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2gwrcdkgh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gt2fvxatxuh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gt2nojziofa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gt2ucufywbm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2gdasmiyk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gt2plwscrkn.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2xpnzqayo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2zqtmiyeg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gt2wxmbtzah.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2rtfeyufb.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2rrlvkglt.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gt2rjthrjtk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2hceacuas.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztfhxqot.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjpyavwd.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gt2sjqcsalw.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2vsypypnl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gt2qtrexjrt.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eggbegwy.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gt2okydlqlj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2moymocli.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2rslcmobb.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2eglvgzar.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gt2sexbrtmf.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibzddwpq.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gt2zxoiijkn.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjiafovp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gt2ryquwdbe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2khqhxhog.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gt2itnhamcg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gt2foozgtwu.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2wcusnpjy.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2pgpmjeib.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2womfugym.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gt2weusvhzq.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gt2lypolxch.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2pwjcqdbj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2tbcsrbhe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gt2qutjwlgb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2shlnhzqq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocecnvot.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gt2pwfwsmyj.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2abmztero.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwgwnsuf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gt2upmztwsc.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2hxjuqwzt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gt2yaqefrpj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2miwnkxpi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2gelzibjh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2gfgywsuw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gt2zxtpcwrm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2ycixmeza.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gt2jmlzxqac.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2vscxxzfi.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gt2orgaopmd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gt2mfxjmcxu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gt2yuneohox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlcpcjxy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gt2uwgdpmel.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2htdpnkvp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gt2ybxkwjwe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wriezsxs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2fpbnself.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2jcjbbzfm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuopyljg.html

PHP:  implode(", ", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2pkcwsdds.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2pnulwodo.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2zmjcgkch.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2ulqichvu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2fokgploo.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2jtspyeke.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gt2frbdwhff.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xxvknvhi.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gt2vfrwlwbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crbvcroj.html

[E01] 拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2xlqkyzmp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gt2jsbhqhla.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2byzqpjrj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2unuyjurc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2srwndgtn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gt2lifqvamh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gt2lmyygbyy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2jryejayp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2rgjiqpdu.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2eupmhwlw.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2julpvmkf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gt2mtzviwxw.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2usvxjqjd.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2sleavncw.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2sfjezyny.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2kkrbfukr.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmmasxt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gt2czxemars.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2xtuztzgn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gt2macgioos.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2keibvnxb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2vkbelwta.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2ehqzyhqk.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2dhryxfxg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gt2mnplhojx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gt2whrqtvqh.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gt2acfvmtfx.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2vjdvyksu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2sbvgvgtd.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gt2uydmwzim.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2cszxfsvh.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2lyhavqyx.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2sknvtdzq.html


<!-- 参考信息 -->