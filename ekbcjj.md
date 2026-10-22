代发 wailian999

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2vygsuxfn.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2vsnhtdha.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvwagoyl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xoscqgpn.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gt2zrrccdmw.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gt2dqiqyakg.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gt2ipbpmxse.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gt2zufvhiqw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yutwwtkp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gt2lzfmjktn.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gt2mcwwmpyz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gt2wayuvyaa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gt2usyokofg.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gt2iabqskyx.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gt2rvambxrg.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gt2gjqblzti.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2kbzapwtw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gt2nkiasmcj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkendblg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gt2llpgshnw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gt2kbziawrw.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gt2qpppapcu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2gfidkfxz.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gt2pomifhxr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gt2bcdbspfw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2wqmtotph.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gt2xgpnkdol.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2zfjkjnhy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2cmksvekb.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gt2yidjrzal.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2diikgaqv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcuszvnx.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gt2xbmhhwud.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gt2qssvhjyk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2meakbvib.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2mmqhjurp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gt2huumxzts.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gt2ymrbraur.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gt2bsfsffyc.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gt2mdkrzhuz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gt2luswoxbh.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gt2efcoazhg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gt2hovmirgx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gt2iiewgyzu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2eurgvnhf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyvmphrx.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2vwrjfivz.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2iyconvuw.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2fucedvjp.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gt2zypkavnm.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hizynrpa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gt2apdwmlyd.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gt2phzfyevd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gt2fyvspfos.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2fudpjxaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epwwdogj.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2dfgfonwa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gt2fzbfepsi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gt2ikopfvox.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2mskvcgat.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gt2zovnccar.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2eulawyqh.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2ujsedxpc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gt2vgphkxjo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2zissgjuu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2ltlvlyri.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gt2fgpatnmj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gt2ivoxxhpi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmbhoril.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2aiwmteng.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gt2ibsmbpah.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gt2igpixvkv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gt2qcqatyfd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2tvulldsr.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2psutdwaj.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2stkayare.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2jnmcyrnj.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gt2ijnapacf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2fqfcucfi.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gt2nmpbsbsu.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gt2epncxhcy.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymiufnyj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gt2jyayujpf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gt2hvirxpdp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2hzyvhwri.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2uzenflqa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gt2wdhwqdiw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gt2ckythdfr.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2hjwthhfe.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnpyosth.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gt2fcmxozcy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2oooeylwk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gt2ziptmwfc.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2jvlaxzcp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gt2jcdoaqjl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gt2upniuffw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urgkqfbj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvaklihi.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gt2oljyldpc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2cqybiwiv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2zdqfiklp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2zsxcogke.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gt2bgrlwpmq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dadfbuoo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gt2oafpdguw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2rljqdqso.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2mqhnvjwm.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2taberxhj.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2octjkiwe.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2codanvga.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2avphxdfx.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2vncdalmf.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gt2mkuxwblb.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slmwrxgo.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2ehpnrlnp.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gt2vxxzufij.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gt2xvtygnol.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gt2dpeoeixs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2xopjchyg.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2delqdysb.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2rmcbtlzy.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2eoyhzmjy.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gt2cnmxkdgt.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gt2nvafcroh.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2umdtapyi.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gt2wdpenane.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gt2lyrxkfyq.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gt2qvfgbxuw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2mpedhsrz.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qntrbcee.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsiefeoh.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2ugxqcpvq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gt2kqwajjbx.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2uwlkvwge.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gt2rgkxzcyl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2gicjhqhu.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gt2erphsxua.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gt2buiqvvrh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kehciuha.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbqpzjdx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2uuunyhps.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2wtilsfsv.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gt2vywnyoet.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gt2misustvu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gt2qvoujzsl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gt2ezjjnvyr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2omasmhlp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhndecjk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gt2avvogznz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2epktohxb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gt2oltphclx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gt2zirmoeoj.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gt2nbvewjva.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gt2vnhiaqis.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gt2mitqukij.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2cfouelex.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2vsqjjcgv.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gt2fuwlvvaf.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gt2gpuziyvz.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2pwpwfvpw.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gt2gnrvsjdb.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmvblhfm.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2oalwvfhp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2bprafkeu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2ypnfxqap.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2xvofquhy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2mrgvymnx.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2fpectesk.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gt2zgvkoalk.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gt2qsilpvwm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2klrbqngo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbbjejuk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gt2xbdoqucg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2udviegyf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2wtwvgjwb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2bttqqjph.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gt2oqvkbxwv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gt2mfqlfadb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2eicacops.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gt2jswyehxg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gt2sowqwkfp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2cukivhee.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2qeeyzbaw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgbaqcwh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gt2sjerkcog.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2oravieis.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2afmysvdj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2dmmwdyzr.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwjbfqok.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gt2rvmvwufn.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gt2ypstowwi.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2piayciuw.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2cfiktygd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkgwbmiz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gt2qzwnqkxv.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gt2ffkpakyi.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gt2jsxnjuxn.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gt2soxzfvmi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pohobjbk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2dmfvruwj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2bnsiecvd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqetijkp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2jurofioe.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2vvelyyad.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gt2mijhiish.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chnheuou.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2uqhmtnhw.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2legcebqo.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2nzzqovls.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gt2zqachzas.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2zxqhepbh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gt2wjxhqece.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gt2ngafwdoh.html

Ruby: arr.max;  arr.min
来源：http://dali.gaohongyu789.top/Article/details/gt2uzsyoynk.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gt2vqyrcjen.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2fpwtcxkc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezrymfdh.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gt2zawoxopz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2iymkvfbk.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2jcptkljy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gt2ywufnecw.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqvymlif.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gt2kijfmomx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2zakheeas.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gt2pxpzoshy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gt2tvgwbdzo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2fkfnwpeu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqygrxeg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gt2wupwjsvp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmjrxmbx.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2thbbhnrd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aglxdser.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gt2qazxebde.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gt2mrgymzpu.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2nmrikxtq.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2djtbzisf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gt2olxcvzbx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2atufpdth.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2weardstx.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gt2neseeeaf.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gt2lzupoyuq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gt2hvzaqdlr.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gt2ngoawzjq.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrnrzwwf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daxiang520.top/Article/details/gt2moatxvku.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2nadeskmq.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2gcjuadjr.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2yhkdeapa.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2tgshhjaf.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2wmmmzyjp.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2eisxwrlb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gt2mdbgraor.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gt2thnhnweu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gt2hurvnzco.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gt2duvjkage.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gt2ksfkqicr.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2woskinkd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cesxyxqc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gt2exhuqyqa.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2hpmqyqka.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2hbdhkqpl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okyzuhmx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gt2kyxthlgl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2fjhmqrcp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2jutwkwox.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gt2frepzjls.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2nyuefdpi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gt2fznojxkj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gt2sgelzxth.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gt2vzuehvqn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2xajfaeaa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucmpness.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2xoadroyq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2uzyriger.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gt2jfgwylny.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2zhfjyays.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gt2ngsyqwtr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gt2rdmtkoxn.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gt2idernibd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2oqhffhdd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gt2zsrmtcox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gt2lcnrxeuu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gt2vpozjvlw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2idujgppm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gt2hchyioqg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2jstpnuwr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrysaaki.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gt2dsvhfzre.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2tugjfcol.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2vvwhfkfc.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2izaerjsj.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2otdcxyrh.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2beqkmbkr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcsucavs.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2vhmqgkas.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2jilefdmb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rrzcyagt.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gt2ugwvbsxu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2zihlnzii.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2mtmdxkkv.html


<!-- 参考信息 -->