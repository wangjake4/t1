代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtnfkzwsld.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gtwxcfyzbk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtvncfipcn.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtmobkiqmp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtmxqexmib.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtbkojqdjg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtvvtphkyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtpuylhytp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtzzwdymte.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtcukitwxc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtqkfsnpqz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gtiagnsddg.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtjrzdsbcm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtvpktevpm.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtcfqvjkqo.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtotvvngqb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfglzmwkm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gtnjjidgwc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtoytsiaep.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtwuveshpw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gtpbdsjbmw.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtzwscxuqh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtgtpwthvp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtvkvtwuly.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtodsmftlf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjrmygcsg.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtsxedfngi.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtrgkyjnys.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtokxyvwri.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtncjbbcap.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gtwowxzxcm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtmcficzul.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtxlkgytvr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtojwikkdi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gtyuubsydy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtxvwzcstf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtjmmiyulr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gttitmpxxw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtaqlkzeyq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwupumixr.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gthajroevd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcisukfon.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtcmucywiu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtjvlvnmqq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtttedhtvo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbkchzxt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtsgafatla.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtsakygebv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gthvsrmfhv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtqyyqgprz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtakzderqo.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtbdyucpta.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gthjbygwiy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtuedhtfgj.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtfmvzrorw.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtxibftmcd.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gtxkhdcala.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtqtsyjpfk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtguxsbbmr.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gtoojhxufn.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gtysxznctb.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtccpcyjsr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtnibqcbcd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gthbawjgar.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtnwkusnwp.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtnhffqzvm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gtbsuosnwj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gthnkceazj.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtrtrqrgob.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtrpywmfst.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gtudvpzwpr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gtctjunjun.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gtgubqbovh.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtmqztwhab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtegkgoczk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtodnmzega.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtvhninpom.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gtvhxszokd.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtbwrtrgkq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtmdxamwjj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtmktzbicp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gthesyxhac.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtmgmcxqxg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtzlbmoqeh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtzfciccee.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtfvgkwurc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtdlxrxlfx.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtaqsdkemi.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtbbgddjof.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtdbxlrqbz.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtohskpsjp.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtvsryglcm.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtyiqatoqh.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtbvseinwz.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtgjvfnjus.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gtfpkzukeu.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtcdehdjyq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtxsxeaael.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gttbusnkfe.html

JS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtaovqxvbi.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gttjqmvixj.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtahizkwtj.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtgznclykx.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtwvzjwrsg.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtlnhezsii.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtvrqzimzc.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gtsenifpap.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtdaenypry.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtsvgarprp.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtjkgsxxwy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtlwudlurj.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtqckzjbqn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gttuppaxys.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtydddkhpb.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtadrmyhcq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtxlipzwfb.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtvfkvafsr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtvaiugtno.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtoczogznm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtduzzqkqr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtacvjfkta.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtgtibjxkt.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtmibnqhkl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtrjotjgvc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtdtxjgthr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtaegqcplv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtfevihckg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhcmhxzr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gtbxcipxso.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gtuhetuycc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtyqnkemyi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gtuzcwnfls.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtsdltgtvh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gttabdwyym.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtbpvqzigs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtdzawdjqj.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gtjxwleiey.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtogbdlfsr.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtpekcvqgc.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtusembbso.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtuflcpsjf.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gtazmmgajb.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtakczvwue.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtzwhxkhgo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtidomaibv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtbwantswl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtsekebhmx.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtzkdibojd.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gtrkazymwz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtglodijrw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtzcmvllrd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtklrtslsd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtvavbgdzp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtunqfcwnh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtjhzucyby.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtuizpagfc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtctebktlu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gtftchdfnj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gtqfiwrrnt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqrcfuuk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtkukwwefb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtwjejmibp.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwjlognxa.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtpzmdmpup.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtgcwrpitv.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtfgpfzhvx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtfmcorwrp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtxnpdqdxm.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdswmaxrb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtuvextyhl.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtldtsomno.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtmhcmtjjx.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtxcejtwgu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtrygywvpa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gtukeptxxt.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtcdgwiyyq.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtpfetxfxr.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtobkstoro.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gthivlsdtz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtofwbzzhl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtrsmupwnb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtgcektkfl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gtcibkkqxw.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gtpgajbbht.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtfxjwqquq.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gtvunurqcm.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtachcabtj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtagdirylr.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gtttzlstcr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gtfmdmtznd.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gthtgxspaz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtlpdsgwmb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtrrdonvxn.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtnocybeki.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtcdaaghku.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtagrngffx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtvylpldou.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gtkokrdong.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtgzqoqeuc.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gtnarnttnr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtrxvemwzw.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtcaafefqh.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtjxlvlyqq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtpyfcoymo.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtnsbnacjh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gtbqbqyzqz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtcukqoivw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gttcfuoqgd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtcsxlweug.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtsyutqcae.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtvthhwtdl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtkctszkbn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtqmcrqmnr.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtijvhplgs.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gtcxrbiipk.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtiwginfrg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtqfqsihbx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtzpxpknhv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gtibzpxuuo.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gtgerlwahv.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtxogxtfza.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtbwqjpwxy.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtolsklahl.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtdmqhlhvw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gthieedbtg.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtkobenxmo.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gttyhalfvf.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtlrbixfkc.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtbirbxisp.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtivsxjfbo.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtdbefsnnb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtzjxszuxj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtezmdrjrw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtzpzhpffg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gthirtejgu.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtxihrscmi.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtqemoqadx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtmfwzxrga.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gttajjnrhm.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqcxabtu.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtbhonkbgm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtdwxcvnvb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gtxgeoeqwu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtlnubpioh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtaeqrdgge.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtvlwtwovd.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtekrrcwlu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtudnzzzpy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtbowkfyju.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gthflmdxtr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtgnhmypsx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtiohfymzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtgoljzubt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtdzzcctqp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gttgzrdley.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gtylfrkwkx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtdnctboxb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gtltfmhsfa.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorgxhckv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtajzuglwi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtvxepjcbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gtgckqabhz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtsyjxwvzn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258888.top/Article/details/gtpocmpfaz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttepnkykp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtdqgaavak.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtkhkgvvep.html

[D26] 数组转字符串
来源：http://dali.hfpthk.cn/Article/details/gtehzoxmnt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtxhhmuhcb.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtexxfvwhc.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtnjbsbpak.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumrkhmvb.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtxairsuzv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gttriupsop.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtrkatwwte.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtpkubhrmc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbmxxbtky.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gtnpontyud.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtekrswrps.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtsfglitrc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtjyjyjqvp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtthyxtlna.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtccfksfzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtbxjsqbye.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtcpyeyxvj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gthcqmctcy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gtpbusshkp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtnfjjaqra.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtahkgmjyr.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxjnkewc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuanzhike.top/Article/details/gtdznuyrjk.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxsykopi.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtsuakyffr.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtdxmryxqz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gtcysccnzn.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtfnqaycyi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtinqbypnb.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtarkbltml.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtudqekbhn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtwvrodqol.html


<!-- 参考信息 -->