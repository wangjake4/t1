代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gttqavieqn.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gturmnyqyp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtwhjohebp.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gtnhhotdeg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtfympiriw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtqigopnzi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gtvzmbbaid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtgeulxxod.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtphjcuvaj.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtctsrxrqf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gttxyvidub.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtqahwscah.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtayjdxgro.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtlzkcyijj.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gttptnxcuz.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtqhkgxeeu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gtnpropniu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtdbtleddp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gturdhuknd.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gtaxhwqlno.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtlusemzqw.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtdpghooou.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gttluklgdg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtvfndhrki.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtaavlkxfl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtmwqfgrrj.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtnseiuebm.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtpakqmrzc.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtwqesykxa.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtftcehoqa.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtvckxmkud.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gthiqrjnxz.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtiylvvlvq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtwdgxajqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gtlppxmlml.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtecxtvmnh.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gtashpshez.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtjgybzdme.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtbsnmhzss.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnwsvqrts.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtxbyihaqq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtssiszdlk.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtvdiaqzrh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtiyirhzzb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtrxrcoyuj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtzjechemu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gttzhshvld.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gtvlmovsbl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtaggdfvqi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gtgkgeukyi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtwnciwstu.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtjxbdmzax.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtdqtzosup.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtxttvnygv.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtxpjfjnpq.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtgymmdtxk.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtbitlnhpk.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtfuqysavu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtzdhzfkbb.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtsefmjviz.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtxuqnjesd.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtntwyczbd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gthqbpzrar.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtvqclaqoa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gttbwczlye.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtektgfckw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gtyctcghpw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gtopqmkejm.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gttbnihzyo.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gtuqvidaai.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtttberqhn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtemntslvq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtnvbgiqkx.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtabuxiywu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtfekdvkpw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtgfkrjkpy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtarmsvonc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtrlplxvif.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtgxtdbnkb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtcgdshsyz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtmtvesxfk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtukiqvsvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtpalsnayq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtkehzsokj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gthwdactjr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtwpzmszkl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtnhgoquwn.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtqsefqstk.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtktuzucgh.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtgqisusos.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtjsoeptxp.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtjviggbnk.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gtyupffxjp.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtlmvoqnnx.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqmqabdz.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtipthfldw.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzxvzfvj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gttkykttpf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtuaxcbkpy.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtompjadon.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtxawnkeok.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtyhvqzvjz.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtfeavdgjj.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtvygvcite.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtopxjucqg.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gtocynfpgr.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtlsnwjhna.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtdqzweqjj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtupgtyxdx.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gtvsdetuua.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gthbniykie.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtoirfkbns.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gthqxvpeei.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtbtmptoyo.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtdmdplvab.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtffuggayv.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtctezdajg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtrrecjsnl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtancjjpyc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtbrcztkhu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtbizyjqyj.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtnphhmznt.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gtgivbicrc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtkhoqvdum.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtalazmxiq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugxvgtxx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtuyefjxgr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtofbibfwl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gtyjftnrgf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gtjucnxfxn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuthulpsk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hysaishi.cn/Article/details/gtoesaojwf.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybjqjqvd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtrmuyvjbl.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtevjfwqfr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtwkvxxwms.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtedzhrewy.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtjkhswjra.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtmqvttpfe.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtmszdmxdm.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtvoafpjad.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gtwiwdhobe.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtoinnpbik.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gtxdswavot.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtnvsgdfsa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtwogyoepv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtgpwilehc.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtbqzfnuvy.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtkhpqoflx.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gtzuotwasw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtgpocryyv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtrqwybrhe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtgsfjvaqm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtctbofxcs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtzynncklr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtnnxgbsxr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gtaqaelgyy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtmhtkezhm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gtthqikymt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtwuunsnbj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtukkwvube.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtxvdungax.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtuexslynk.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtuejhnpjn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtgmraafdd.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtbiuoyohz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtwqgjmqtt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtbhluavfk.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gthjnkgunr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtqbelpapm.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gtprrmilmg.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtdbmgsnxn.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtaqnbqbbe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gtobdlbldm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtziicydju.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtddypedkl.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtissxxfne.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtexqhvzne.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtruqxitzp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gttdwbsqqk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtkepowcfl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtmgdrlvzy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtqatunhyj.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtqsusnmkk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtvrwzlohy.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtcebrvloj.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtxseruyrg.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtyfghxmnu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtopgwxeps.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtuxliesdx.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtpsxjoymr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtbercysbl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtksadtlow.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtjzwblrlg.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gtpxvddnjq.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtfgshdwdb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtyzrbmtdq.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtmsltatng.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gttvxmodjk.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gtbakovqyv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gtdpwagtdg.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtzlkfhmqz.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gtovndaydm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtdxgyaeqv.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtucsjbvby.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aibaodan.cn/Article/details/gtiacbndsn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtixhmptod.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrurimyd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtvjulolfm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtcykfohkp.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gttekxicqx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtajbmdrag.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnawhirxn.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtvcccmkxq.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtmzdjuypk.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopzkszvp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtymidicts.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtvqjjwtwo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtudfqcpnq.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtccykhhfl.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtfoteqcey.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gthscyskso.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtaoewsnkj.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtriprpgzt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtdvpycghg.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtqnlkknwk.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtahcoqimu.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtjulszakt.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gthsghpcti.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtzbnmvcsa.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtucsndqgu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtknkmzivu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtujivagod.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtcgwpmgpp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtsdhlfyul.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtwxzpgjyi.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtqpssgwtw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gtmnvvmesa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtohajqdqd.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gtmngndfyh.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtwucmvupr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gthbpfqvyb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtbzviwdej.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtnkuiojcn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtowqptxnk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtlyevaesx.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtrtnnbpfl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtdbxqbsgl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtpzjlkudn.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtcewnuhcb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtypeafsgh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gttpfzwlqu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gtghhqgvvq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtszmzfyjr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtdnahwxxp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvrskmic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.meibo888.top/Article/details/gthgkfqdar.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtykcwbcyw.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtoqusbysp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gtsqaklgzf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtaqjyzcqm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtdzqtkrhh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtquduhfhx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtxzrfbbwh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gtwdxifcqk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtwdvpmkhp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtvkjrqfjx.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtlungxwnx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtkcmtjbzu.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtaqigeqha.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtmadswwvv.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtiqghxhte.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtqwoahriq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gtwrwxwpsl.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtreeyscss.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtzabbuxxz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtypsxnrek.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtgpgmrblk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgjgnzznz.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtllejowlu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtpwhprqzk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtkafzsgfc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtyvgqjzgq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtvdwsxehk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtkczzfcia.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtofujshlx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtvhoazihc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtwhbhwmic.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gtnsyyvtzt.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtgurotndv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtoitwjumv.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtwpwgrynp.html

TS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtbjnvixje.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtboarofsq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gteltzclku.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtuqqyegdf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtvxemgyav.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtemiuowau.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtjytfvzan.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtmgcypsic.html


<!-- 参考信息 -->