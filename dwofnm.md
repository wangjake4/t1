代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gt2xrqerbmf.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2wjekyufc.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gt2stngrfbr.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gt2pfjigovl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gt2ufoznxjg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2zsmzcjxo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2bwnvyxte.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gt2oonmuvul.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gt2uphhgwjv.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gt2yzlnndug.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gt2uyneornm.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gt2yfvfitps.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2ypjwicwa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2iouxnfbt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gt2itsuulqm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2owosgqfr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2cwrvztxt.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2afrutjgq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2rouevkok.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gt2olttpocp.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gt2pjjqcfhc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2iugkitoy.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2efkhdhud.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2kcskxpre.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2maornekf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yltcfvkx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gt2bggjzukj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpemkeb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gt2hxfngrhm.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2oozflcvr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gt2kijasabb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gt2bbdtlyck.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ywlaexvu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vawwntia.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2zuvkexuk.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2ricutvpk.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gt2jbvnevwm.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2osrcxuud.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gt2luhfnroa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skfkaoea.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gt2tfujlhii.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gt2evvfqaxi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gt2okexqvjt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2uczrnjxx.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkgofjgq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwrvhkqa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gt2emweiqdo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2tgfuohtq.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gt2ciynpbur.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zaebryje.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gt2ufliebzk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2fpzmdumh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2ekubewlh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2gjociomu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2jrlgmqhn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gt2uecvaqlh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2qwipsigs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gt2jmtvayys.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfglfhpc.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gt2nubilkrf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gt2ooqjwfyj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifnepfla.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjsburnj.html

TS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2befkozuh.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azpeixkz.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gt2rnwizxrm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gt2pgibjcqm.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpusvlzy.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2ljpurjoa.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxicqknw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgvqbkkk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gt2vneozhbd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2flfkcdcl.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2uvwraihg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gt2welfnvdg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewobzjmt.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2aweytkzl.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gt2jjiixyah.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gt2rmpsdapa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2owmuzytr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2pqjhgfbn.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2fzmgloxy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gt2affkwwzm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gt2ucuqvhwe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gt2uyjlegwc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gt2ksivbebm.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gt2pwbtujiz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2byfqvnle.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2pbwfdsky.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2ekjbzvgu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gt2gnwynkiu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gt2mwjxlvgb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2jzfkaeju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfbirltf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2ilwtvxfv.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2qiraiocz.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2wjddquyh.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2ldepzouq.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2cmvcovjd.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2cxoftbic.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gt2wcbzikaz.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2aemdcijb.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gt2frezlovh.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2vrcafcqr.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2pgxiwjay.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gt2taixomxj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjzhpcrj.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2gcmfsqip.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2ddsklsvc.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2efzhlroc.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2xyrnbfvg.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gt2fxcvoboh.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxpdpkjt.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gt2wukglvqs.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2hubrefqa.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gt2jsbizpau.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gt2hifuzscs.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozypnqdk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2pgsupkwk.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gt2mzsdnakl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gt2kihoxiup.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2dxtuvumj.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gt2qhjfrusi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldqqevzp.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gt2dpdmffwv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gt2pwreudmw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2vkchrvfc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gt2bylmdjli.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2xurzcliv.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2fvaizddh.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2setpatrm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2eztobwxn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gt2atygfnna.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2cbxsixln.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2grtqpcsp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2ixdhnbbq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gt2rwqsrzlr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gt2iauiazsu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gt2ansykwor.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2jfkuwshe.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gt2epojssrf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gt2szglrpzs.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gt2ylimavkz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2ahpsequd.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gt2rcautfcs.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gt2hcxabttp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoanjlm.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2zwnvhiey.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2piajurod.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2iblpycjy.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edxwrhkc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2xozatggb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2osydosnq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2gffeggie.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uaxzimzz.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2cesxwsuc.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gt2nglqomuy.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2qydpxyhp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2odwmkfpk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gt2xoxqbdmo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2kxjeuuzx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsjnuwyj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2yjdvasud.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fufbyqen.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gt2gttgxsgz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2diocbivg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2onhrmdhc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gt2thurygff.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2ajrymyvv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2icwipvwc.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2mhamxtue.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujhdkvcq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gt2xxtftkyy.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gt2fwgwvpqs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvalrugi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2wdaunrrr.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gt2nlylmjeq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsccojfc.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2zenckejt.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmfrxntn.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2sgceqbwz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gt2ufotulvn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gt2jmptlpec.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atlixkmf.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2gszqezpd.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gt2mgrppbht.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2elimeoyb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2fcdtknha.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2evhjghgy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2elcquqcu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2xfpgappw.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gt2ujihbhvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2kchmitru.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gt2crrdltbg.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gt2wgqlmbda.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2fdfrfbod.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2iwrdmfxj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2qqlwrvkb.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gt2nqzsisso.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gt2upnkstfl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gt2eyfqxpgl.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gt2gtfslyif.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xncflyqm.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gt2gdjhstnd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2vfnqvmqf.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gt2zhzhwizp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gt2kwaedceq.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gt2jxmghlxy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2ogjfqcau.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gt2ioyswhfc.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2eabswaud.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2fwsnoxyz.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2znbyyubb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvyvwglj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gt2vwmiirij.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2kninyjpx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqdeoyiw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gt2ddnoroef.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2xjmxnjtc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gt2myjnzxlz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gt2tmxfzffy.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqghdcjk.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gt2byyzrzkf.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2nbpnaqmu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmkmwfyz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2lihyxgvk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nslszkhb.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2frdewvne.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmsofeow.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gt2uaqkrgvq.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gt2fnlgyfrb.html

Py:   x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2glugepnx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gt2ldqmjetp.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2uisppwvl.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2mxcsldbq.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2kvbtcexo.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2cltfrpfj.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2iiapoimr.html

C#:   list.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2byduzqkx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gt2dzkuguoa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2thbdaotr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gt2amqzohcv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gt2kywqixig.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2lnafjdnu.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2forofpdt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2jtqhyrki.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2blolncka.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2rflkzzeh.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gt2midibicb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2idcpaedi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gt2eigadaun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtswjsy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2svxpvcvf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gt2ibpewjgf.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2whwnpqlq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gt2zsgvdqpu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2odkzinkg.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2smhgtjlu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2dhxuddqd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gt2lujmxkat.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvpzrpxc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2blixrsdo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2acxwcgty.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gt2lqxphgzc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkbgyjgt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2anwsivwp.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2lverjyka.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2gqjifgpn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258.top/Article/details/gt2nfpiccps.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xykalkyu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gt2gzsggenj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2drdfvbip.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gt2eyrwilkv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gt2yrbcdmde.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2quniofek.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gt2fvfmclzv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2pjahxdtn.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbrxjeya.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2zzuqocug.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjywkqhz.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2fdoretvj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2louuovor.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2qdopxdiu.html

C#:   string.Join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2puxbnvip.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2sxdjqyjf.html

E. 字符串处理
来源：http://dali.quarkkingdee.top/Article/details/gt2uqwcbpzn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckahxmbu.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2hvtmiegr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gt2iqtjvgwd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xziqi.cn/Article/details/gt2mfqcvxad.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxejahea.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gt2bqqenozl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2lanhgfdm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gt2veguunuo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2ldnebuzk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2uipuxyrx.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gt2rblbljia.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzbnvljh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gt2nnkzjojg.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2frayolgd.html


<!-- 参考信息 -->