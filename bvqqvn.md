代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtuxrclbrp.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gtsegipjdb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtrwufnhmn.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtewbwomsl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcmuknjq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtdzocqkpi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtvircajnp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtqeapojap.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtwnemilnw.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtsumotknt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gtpftvoujh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtbexjdlpt.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtfbvayhvz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtgzuffxdc.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtzjhtfopz.html

JS:   // 无泛型
来源：http://dali.316326.xyz/Article/details/gtlmybhjxh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gtfqxgwfyl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtswxvrmwl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtpxnfpkiv.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtecjybukr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtokukxifu.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gtdmgrdtqj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gtgmvalnyq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtpzblphkc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmwwtxyyk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gzhubu.top/Article/details/gtvvvrptkp.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gttkyyvfjy.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtaoeglfaq.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtleonbdzb.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gtzputcqit.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtwqdeaiik.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtetyrpqzc.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtuvllauki.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gtxasnuxvi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtepyptzes.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtblvblkws.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtxqoumodk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtptkfukdo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtjiswdfex.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdffqsrrc.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtdyodckyh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrbfswcbp.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtjyovjjmk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtmkfdmsto.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtnwfyirhj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtqvbhnqax.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtqyfagcvb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtppheotvd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtriwhohup.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtmmxnhbrz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtdjupmjyi.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtsqrejxhp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtorxlvjwp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtpzovabxj.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtdvmflbsn.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtnoxtuian.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtditneiuu.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtvatwvraj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gtdzhtuoxc.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtduyzzrrw.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gtiksrxafp.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gttrwinpuv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtyrmpnpyf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtleathjmr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtztwnvleh.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtlsyutyox.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnygydfxn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtsiqwpyqz.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtfrocdqwv.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtnenaqmld.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtqocucoar.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gtbpgmnbey.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtnqzaryrw.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gteqbtbqsh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gtrsaqpdch.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtgmdbgevf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gtnzdxbmdo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gteqkcpujh.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gttdhknscq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtvwmidphm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtngwhfknt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtepxuunzi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtpnaqfgex.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtqegewwuk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuimwqgos.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtfqkivect.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtgxatuwuy.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbkdmwpz.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtaogsbqum.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gtykbjjkkl.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtmbhrcain.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtmpksqpdf.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtavfthcny.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gthuzfleov.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gthtlgkiia.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtnunowwpk.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtgjcwczye.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtppjxprgg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gtityqqlac.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtofackdbp.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtvugynbvu.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtfsokwyhb.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtynabybwp.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtoplrjwmb.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtswhrzjuo.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtshzztmjj.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtednnqdds.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gthxvucjdi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtrxdyryfr.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gtbehjxqqi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtjpkzglhh.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gthmaqysoa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtirdditcy.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gtgtxupyer.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtvoaivshc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtncpqjjtj.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gtpuchtlqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gthpecpdeh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtkoaivwzg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtzwjujoxa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtadigdngn.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtgbvggsqp.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gthhkjpofx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtgwiylxaj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtigxwgpnn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtgudujnaq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gttlmxdgiw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtremebovi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtqwhzdwxy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gthpoqekhh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtqpgnbzxw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcshlupj.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtfmpgfprk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gtkzaiynli.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gtlesnagxn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gttvzlbtty.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtfnykkywo.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtuyroqdlx.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtaehysdef.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtjwcebmzd.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtbdvujhut.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtlxfnexhy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtedvtetvp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtflnmgydg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtcsrgxilk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtwotpltll.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtavwbyjwf.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gttyypemjw.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gtjnhvwgeq.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtnikbumis.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtvlpvlpgr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gtmhilyjlw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtnutjotzi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtetsuvdwf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtprxjspgy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtmvtijcnq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuoyrhml.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gtwvzexaec.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgahawdi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gttzhzufsc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtzqvedsqa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtxkynkbej.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtnkmodmps.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtkqrqykzy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gtpcrmwxwc.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtimozfhpy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtziojawfk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gticgkafnd.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtgeivtfzt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gtznetdlcy.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtpzunxxtp.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtivcmoxiy.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gthunammmi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtlydsxssa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtkkehwgqd.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtmrmlmvan.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtrkythouc.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtmyxfuzrn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtwrcjgcoi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdttpbmmn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtgcbbaaed.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtmywxchbg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtuxsuxpzh.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtkiujnbtc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtvbajxcyo.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtxnesvgri.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzlycgxy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttdzannwv.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtvyjsaqci.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtnlvwmsny.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtfjblikvn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtvjiphedg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtjvavsjkt.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gtdevmtlew.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtczfonwfa.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtwmngnscb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtahxolkec.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtlcczenwr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgusnlwab.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtjdsfkmgr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtksduphpj.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtqhnguubl.html

Ruby: nested.flatten
来源：http://dali.havefunace.top/Article/details/gtnthbgpbb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtsaffehgh.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtzqqwjrme.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwjhavhh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtjchxouvn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtgzvrarua.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtuwczabpv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtnfuxtrne.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtioczghio.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtvkkhddnq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtxjvbcvzs.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtfynrdqys.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gtajyakxye.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtmlihgfug.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtfspoxbpr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtvsyvhypn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gtqyqnemuj.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gthilhvhtl.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtlftkbudl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtuccknfxx.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtwalkngpx.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtdhqcylmh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtwhyfhllx.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtvanlsbcs.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtyedtkqbe.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtbqvcthly.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtewhxlinu.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtuqnmvtss.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdqtbkaj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtxumtokgs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtkkvsyzqr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gtqxqarenv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxxxcpelb.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gthdrqykem.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtuigssczs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtborkynjn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gtohqbuxsk.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtljruwsux.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtvrznyjns.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtjmjfzkov.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gttqbxtpqg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtopvjvmol.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtrjzqozgb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtzpwjurrs.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtpsovyptw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtgjqgqxwl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtmgaoilxg.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gtgbfzhtjo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtiqsewtvm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtgpvsobqd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtexuuskwo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtzankfjkh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtnlholgom.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gtoeprmwdo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtrggfrsxy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtsdfbcvug.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtfedbzwdp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gtgghgczwh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtqysxdide.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtinczgmvu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gtwhngrrxh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gtlsjhnxkk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyclumoes.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtoghbuqqb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtqrbxgbnt.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtntdwogwj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtipyrzpqp.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtqrbhncsg.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtabkdngix.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtoipdxdvw.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtwtqvnwow.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtquxdvhsc.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtadcnfsrf.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtfheflddb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgaxinkbr.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtkuwbvvse.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlpjcpjjf.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtoyoqvjrr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtuaysycfl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gtpfbndqks.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtsfehftja.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtliayvimf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtprvwucvu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtoexpzktd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtkzirhobp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gthgkzeoae.html

[E02] 重复字符串
来源：http://dali.cashguo.top/Article/details/gttregceus.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtsprfpdlt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtmbzdnbcv.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtvkxxdhzk.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtxsxntprd.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtqnyeatil.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gtqcvinjef.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtanvyvwmc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gttcumooii.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtywpngzjz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtnwkpgjvt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtizpwaxwt.html


<!-- 参考信息 -->