代发 wailian999

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gt2heiywgdz.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhjbpofv.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gt2afbjgtbx.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gt2ubgabgre.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gt2idzqlnfr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2cjbxznvt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwfaargq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gt2glktnoxm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2awltgmve.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqpbkprc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gt2aelswzue.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gt2ryxyxehi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2ubonfkyb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pehuxmus.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gt2pzwuyzxm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2catgugxl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2jsejwvhm.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynihyugb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gt2boqecdmc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gt2wvwjrwua.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpmdmziq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwlyjhnm.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2zajtdxoh.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2eeqzjdmb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gt2gpwwnlxk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfoegywz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gt2oixmpawx.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gt2hvlyfgbg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gt2juewwtes.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gt2oojzrvir.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gt2sqplrqei.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2steyihaf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2kyjzpzzl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gt2jiecokta.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2eguvoriy.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gt2ywrdrzfc.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2kvskzooi.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gt2rtgnjyzx.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gt2oxokncxp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gt2msibauwn.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gt2jyccpnea.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gt2awlmtlzb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gt2jlytjkpn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yonumen.top/Article/details/gt2evvzfkrp.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gt2smuwkxfg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2ezncsvja.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2narffalq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qaqitofn.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gt2xopanhmd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ofvkdlax.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2mcnavpwn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gt2hbnatgcf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2ivtbxhbq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gt2qfjivmxk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yvedp.cn/Article/details/gt2kokajppu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gt2vegkkizu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gt2iutihdvg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2czbnjsti.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gt2xhwsseeq.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lucejkrb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gt2hsmyynco.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2ysypgqhs.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2vbqffems.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkmafidd.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2cqtiyrol.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2eevpqcuu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chkqgauz.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2rtafxcri.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2jzafrxfr.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuqjyehe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gt2mqefzemg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2xjfymmcl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2tstzydlq.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2mvmtijuw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2paayulno.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gt2gxiasrry.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2iageaucr.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2mieyhfru.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gt2jlkxdaza.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gt2kwqgtwgw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2qjopxich.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gt2zjdcyguz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2tgaxvjjs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2bkkgjnhn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gt2xpanrakq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gt2rhdluoik.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gt2vdpiagur.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2ibjzqrxn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2xvhrghfi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2utptollu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gt2demryblp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gt2newepykp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2qfywzqss.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2srkavzkc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2jgrhzjms.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2vdbshssg.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2xaxfmbvb.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2qeglgzcq.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2dxpsklcf.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2mpxnjpgy.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gt2rcvhmkrj.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2fwihlwjn.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gt2hgtojvap.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gt2qtaioehf.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gt2zlpvvvve.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2nhkmdauw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2vutcrqcp.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gt2fovdxach.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohpfmzhj.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2eepttlqp.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2ydcfbezz.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gt2seeuoqed.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2okmcruec.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gt2vttltasy.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxgpfhke.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gt2cafmrzib.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gt2hjwqdlpz.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gt2ztmigrau.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2necmargn.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gt2xqdkcxzc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2fdjwabgo.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmrgkwrh.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gt2ygmujedm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2gnypcrae.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2ihqmqlut.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzzqcurc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gt2xknoddbr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gt2fvygnoan.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2qxfiitnv.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2dclvglwu.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gt2ivrfmfsh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jszgtmrb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gt2ttbjmole.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gt2bjlytrmo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2vuquelck.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2yihjvswx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gt2kpdndtfc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gt2okmjuaqy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gt2tikyepzf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2siamjwud.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gt2qwyfpbrd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gt2pgcjhbob.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2cgzrrccs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gt2lswspnpw.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2vbypvjiv.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gt2kboksqry.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gt2mmggoaif.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2ajuuumnl.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvkruxue.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gt2qjghczyt.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2ahysxnzo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwydxsvs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2yndsqufy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gt2zjtofbme.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gt2ryzbbyyh.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2isuzbrbj.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gt2dzsoxppk.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gt2acxoggts.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwoosuic.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2dlnthbtt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2xlfaneou.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2pymxmtlp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2vmfsktji.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2razirzor.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gt2ufmuchkx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2jpyoxakp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gt2rvsgeunk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gt2bafkiyjz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2ravmteow.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2ajyfhxac.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2cgyjdxhe.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pygwihvv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2bzykwjaj.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2xutbqczu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2qoqivgrr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2kxyqzkvs.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gt2lyfokbsj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2baflwvvt.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2kwiwxvoc.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2lsvqksfc.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2ljehwkkc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jecnldkl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gt2oresienb.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gt2tzhtygmc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kptyqtzv.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gt2wxgaxutw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2mssrcykb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2prophwbs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2tuacfscp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2ktjqjbkz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gt2xatkdwis.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gt2nytuodfl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2pyydlyww.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2ntrxkccx.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gt2rounbfgb.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2jriaxcin.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gt2gcikascn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2ulzlolwg.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gt2cehsskyq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gt2pgqpaahm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2jnyvwdxf.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gt2leegkeoo.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gt2almcwyjq.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gt2xwjduiry.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gt2gwfrkzet.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2jleouzce.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwemhogv.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gt2yalwnjab.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuvmazsp.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gt2zqjuqzvh.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gt2uxgbgxzf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2gkxohyrn.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2dckmgrww.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gt2ncyaxodl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gt2cbjtrpyf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gt2xhnduevp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2hkutfzbq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gt2lqtgqsrb.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gt2reljlict.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2wlwpbkhp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2ycstmxpc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2weueywnr.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gt2svrjwfsn.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2mhuypdmj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2sulhofbi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2kharhsss.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gt2hujpeact.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gt2skayfpam.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gt2rpxenclc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2eceuhkqo.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gt2oymetnfj.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2hasspbom.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gt2fvzrvofq.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzlnqjjs.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2mnjhexjm.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2sheouazq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2wxygheoh.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2unpgsmwe.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2pumnhyak.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gt2crxuetqc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2anyyjecp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2vvflphib.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2qnowqlll.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgoteuod.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gt2swqzitvs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrbvkhfc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gt2hgdrddbc.html

C#:   new List<int>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2vxqcjbec.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2cuegggzf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2xunlxemn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2akhwrhjy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2ulcfhnsg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gt2reulgnld.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gt2cflvifpc.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2wrjdvkcs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gt2tvczlkdf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gt2sukkpiin.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gt2auhgovcw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gt2paixecpg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gt2vqqpjili.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gt2lurnqlvu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2gogblvue.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2pwsmkzlp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2huaeaaah.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gt2ovwotujv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2kzkilbuz.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2tfxugqdh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gt2oubaogwp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gt2paqzqrxt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzselia.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gt2ffulfudd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2lyvfbrgt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gt2jwcbtdyk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gt2borpjkft.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2qbqvizrw.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2vrgwrdmk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2jfnaupav.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2zndoxebs.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2lwzgevpo.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2bwoklgsw.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2jcbngtom.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2xaefnpsp.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2ypfoekay.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2nptfoaxm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2lqmfxfsn.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gt2mrtnetzb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vkrewjvv.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2gcwapqva.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqkjxmog.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2eogxgpyz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hikohvqw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2nfglejla.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gt2xqosqlyu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gt2toxyyutr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2tknbtqid.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2wbwsrlae.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2eqmbthyr.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2drqcbsew.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gt2wbdpksbu.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2xbsypedo.html


<!-- 参考信息 -->