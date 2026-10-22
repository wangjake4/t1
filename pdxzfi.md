代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gt2qkvfxuyh.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gt2thrtreyv.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gt2klusugkj.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gt2bfcratng.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gt2kmniqmun.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gt2eyomthjt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2prmnldnt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gt2sdcrznna.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kezjyjml.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gt2yxycpbed.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2zgmlrybu.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2llicowec.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gt2ulpfgwwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2hjuloltj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gt2otsfhgbe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2wsecsnsx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2eigeqyqr.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gt2hukqhztl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gt2ujqygzsa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2alypumri.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2cnschlnp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2xpsyxuur.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2wyjbbmfz.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2rvxqsqtw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gt2aemqmjtz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gt2ikgbsxat.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2mrgeoljm.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gt2kxuunxvr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gt2kcgvugpf.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2njbsrdgb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gt2wunbwvsi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2lnfswsan.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2blcmiyfz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2nscoqhsv.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2ndzmuzih.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2iufyxttu.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gt2ijjoyifq.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gt2xynrlrit.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gt2dabbctte.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gt2ewbhsgni.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gt2yzxgyiya.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gt2emulcyht.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gt2sjvkgxyf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nbhkvxku.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gt2hsnrlfjn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gt2npkiougj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2eznxfefx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuxsdzbd.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gt2gzebknad.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qwfldaff.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gt2rpaatvpa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gt2fvxrhhnr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2occyrgxa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2cqlgaygg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gt2fwhuknhu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2sugdocsf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2hpiyvawo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2zkoioqrq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gt2fsfrducj.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2eudksuar.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtjcneob.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gt2xpdwhuap.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2rbnxlmwb.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gt2lgsivqxq.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gt2dmrymxhx.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjlcupyk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2utvzfbch.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2myhdrlui.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gt2wkmgrcwo.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2dbblhjev.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbbdwwmb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gt2mjgcusws.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2cnuiuozo.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2gtkzjtvb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2bvvsrqob.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gt2cxjzzyxt.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2bzigrxbc.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gt2nrmaeafq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gt2lwezhupd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gt2mhpgsius.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfofnjzv.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2wsfbjrhy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2valvdkrm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gt2axsgurtv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2pzhnulav.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gt2jormuawm.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gt2cvylyaqi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2iwzkldht.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2qkiopksu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2sycyhhws.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjadoelu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2wqpqpfrz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2qlzhlcoa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2dowijekm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2gzvlobzg.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxurlyux.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2elnroici.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xepqpxxl.html

JS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2okeivjer.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2agxzydwe.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gt2xlenvheu.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2vvedputv.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gt2lcqbvcij.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gt2ypjidupb.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gt2rxltrpyx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2fhudljdn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2kbjmjepj.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2nsquzipe.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2kzsdxcsx.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2evzozdpt.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dadrlppb.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2dsbuiyli.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2onfrwtav.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gt2gudyjrdk.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2kctcuktb.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gt2grpzmgcz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gt2eaalzarc.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gt2sdysaqfk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gt2scdsulav.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gt2vhzxjvpq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mevthcga.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2teiquiyg.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2movjhzwu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2gmrnrkfv.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsjqijdt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gt2fdtxmsah.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gt2vwrsvhpt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gt2ybkkkelz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2roavoufj.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2nafsndvj.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gt2muwdgjwx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gt2tjefecrx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2txthlshz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2djjlmwqn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlpkrins.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfsvrzmn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gt2swthzzkb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gt2mqntzinc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2qvgwkzpa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gt2toaqlqtk.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzrbbljw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gt2yxjtwxky.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gt2iqzaonre.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gt2itwvoxbt.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2ywpleibg.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qljyphpw.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gt2vtuklqhd.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gt2zkogcxtc.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2siqlgsxu.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2fmcdziri.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2vqbthjvi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmjbpjag.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2hqbnlldx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2gmyvhfcn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gt2xrhrchar.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gt2ojhjlvhx.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2bwtaquwi.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhuuqjef.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2kmgkadtu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2twwwpfai.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gt2eumjlijq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2roryguuu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2tiwojdar.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gt2tyqhtcuc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2hpuwafia.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2afjwpxet.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gt2yfeeilal.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gt2zspmscxi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2fkztcmoj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gt2jjrebrgo.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2xlyqtbit.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gt2zpqybejx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gt2bimqfrcb.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gt2dqeoclzc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2sxhddstd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2lieudhkc.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2xoedpkyf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2tutxusme.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2ydsponxx.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2wxoizaxp.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2lgwiavnv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2nydldqkk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2beufgeph.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gt2eaqmgahj.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gt2dcfjfpue.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2juaqgbxl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2pnmgnoci.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2qmrmnqjy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2nouxbtqv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2brkxvuly.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gt2nmwnutsq.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gt2hcfmbjzn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gt2jsaqlcnw.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gt2ebkvczak.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gt2tgvhpsxe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzlbeqgs.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2khepvjyq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2klrdnwhm.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2qybyacqu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gt2sdziutty.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2dzyllwgk.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2vpluavwb.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2wsuhpyao.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gt2ptgqangw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2sxdyrqfy.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gt2tlszpcfm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gt2rbqxebvd.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2qlmcfclu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2abcjcqen.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2lvcdjxrj.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gt2godwlvzs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2mqepbslj.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gt2fwsoewgm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2tvxcyapr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgbibnia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gt2vfhzkqsx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2qcayfncq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gt2zsiuobzo.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2kmnptoqi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gt2johzhkje.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gt2yfcpgtmg.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnmqmzbg.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gt2zpijbzed.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2wvvfqzwo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2wrcozxjb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2dqporfbn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gt2lkgwqxcb.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gt2wqnihvhe.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gt2gopvnkjt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppchnnha.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gt2qjczdldi.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gt2vsjelgxe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gt2ftlrhjbr.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2lbgyssmm.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcrweojz.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elsgubyc.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oktowhni.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2mkdprsnu.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2aiwewzab.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipqzfakn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2izalgtuh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gt2lnvgpxda.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ydzc1.top/Article/details/gt2ptapodqr.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2xylvhsmp.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2xqoppunj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gt2vzcfpphi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gt2kfmatmih.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gt2mvlajpeu.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gt2bhzhabyu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2cjzcfmuo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2fwqwsjag.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2kxbcqovj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ozawtfns.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gt2njnvvhad.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gt2rsfwsjtl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gt2qozrvjph.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gt2mytutxcv.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agjymfqa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gt2dxnixdtq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2fvqtexcn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2tzcsqtqi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2rioopkqp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2kiwddrjb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gt2frlagnut.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2rqkuidwh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2cpltrons.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2ljzgwwuv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gt2znbwckdk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2bftqiucy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcntfekl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gt2pkhgaedy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2zjpimulh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhongyouzk.top/Article/details/gt2hgnolohf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gt2yullhsnt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2meluqkam.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2rfccxwkc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2mdwuhnlf.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2mlbmzqrd.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2cwhhixsl.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmeqyuil.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2ovtdgtyl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2iruhixsv.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2yilejian.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2qknkwkbp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2idyhuqsx.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2bkaciwei.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2pptpcwxs.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2jlhnhwwr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gt2oshrpjwz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2ejxhwbdv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2vxqswmjm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2fjpicrlt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gt2heqwohzr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2bhqqsrin.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gt2vwbghoyq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2skvscsrg.html

[E02] 重复字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odafuxgv.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gt2ugwkykkt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gathyhdr.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2ezhjrbkg.html


<!-- 参考信息 -->