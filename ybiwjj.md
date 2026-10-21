代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtdccqetye.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtxchvpkcu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtnebxexgb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtniesnyxu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtdijcosdz.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gtyaklytgd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvjelftf.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtrkngzopp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gthgihhref.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtkpefgdfc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtdojuqksb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtrayztxqq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gthpionapl.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gtdrgigxpd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gtzziskbdy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gtpolbypla.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtqetxkuda.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtqsxrvvug.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtuzkvobls.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gttixppaiq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gtalbvtsvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtipvpfcdy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtoufuzurm.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gtfqwfvnkr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtyvkqtzhx.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtfvxebdsf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgcveher.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtjqibqdgo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtqoolxuag.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvvlryjgb.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtfgnywdtw.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtbisysdqa.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gtngmfskqi.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtdxbzqxxr.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gtvzmnfxjr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtcixvgcas.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtncbfrqqe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtjhnieboe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gtxjenuuel.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtsumgyajx.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtcwphfzqg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtpdfwyljr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjtypitsk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyppyfqog.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtjvkvkfmo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnvelpyeq.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtuxcowwtn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gteagklhwa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtpnfoslvn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtyjbqjgqp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtrkeofpbo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gtifikpomi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtsjsmybcy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtxopknfqu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtqvcnfvnm.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtzftorruw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtwkkotqid.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyaqwtme.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtpecsosgm.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtzyvyesqg.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gtqdjpftbv.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtyylsflhp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gtunwcpblp.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtnmohngiw.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gtvrdpoizr.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtossbnzyl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtxgomzyhv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiqsqkua.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtguseegpr.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxamiijsu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtmdldgfvy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtarncrmaa.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtlabrcgqo.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gtmfyzqbfc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtxejwnzbx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gtitzyvgkn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtdmqfcxwm.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gttoyteasv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtfwthcnzp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gtcaqbrelp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtoysoncxd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gthtecysrz.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtshkelxew.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtmhyjagqj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtghgvswtq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtyiwekghl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtngjonlqt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gthwnqrudf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtetgibnab.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtzshojhna.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtycpgmjip.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtfehkgpds.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gttdswvqdb.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtzqhtbgwm.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtoyzlaxpq.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtmvkrxpix.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gtbitpzkep.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtkjdmolif.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gtwxqhoslw.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtajxnvwog.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtdmasyksg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gttaxnwgth.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtnpgkjoyf.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtrbvcfvsq.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtmrvzwtny.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtigsnioxd.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtnwedqrlv.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtwgvlucej.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtmtltzehz.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtkvgxhhii.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtzddnmauu.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtjobneyeo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gttbhnwnbq.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gtrmxwhtcn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtopsrpogg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtcbnzxmyf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtakjgjlkw.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtzpghnfiz.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtxagjkrxe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtxzqnlcux.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gtazlaitcn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtcbxnysnm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtlfqjrzqm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtpmqdvzag.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtgtzicmav.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtdmahhslt.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtepnsriim.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtyvhbeato.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtihayitsw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtppjwpnlg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtsmtnrdld.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtmdufbpcg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtfkazngdg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtndfdpqqa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtzyixnxgo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtzkufitxe.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtwuuxjwle.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gtakqepfnm.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtkgtyndpk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtjougesek.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtntlsuhhu.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtozfryuww.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtercmjgks.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtdhkmrvgk.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtyuxzyqtx.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtnkxtwigb.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtxewwyfch.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gtyliyhhfj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gteoueacbl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtndoujfln.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtqavnkkft.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtanirmoot.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtmjyeiblu.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtxzakxgpn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtxxttkqrc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtkjqasyee.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgifjshyr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtaponlmnb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtiedhrznx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtofzghuas.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtvqsahyjq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtohpybmdy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtwgbqkwdo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtodblncsq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtknsrxbjx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gtlobedqfe.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrtgbzit.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtkcbzecup.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gtqaeqxjre.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbvgivom.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtgthlilws.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtcxvsclxx.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtufklvbgu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtycccfxwq.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gthufndzpy.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtlspuldut.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gttxyfszzg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtqcrfyjkk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtgzvesbwz.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gtydqkkrsf.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtdptwlifn.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gthrondpfn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtgdhjeqsz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtbcpgwawy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphdryube.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtowvkvyak.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtlqxmqgyy.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gttzzinuqj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyfvdjal.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gtisiiyylw.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtcttwuuyw.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtyztmmdsu.html

PHP:  max($arr);  min($arr);
来源：http://dali.pycfn.com/Article/details/gtvcyafahd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtmhtkjvud.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuoyvwdr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtbxxfuqhb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtawxeoxot.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtvinqrnui.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtiaknpjwm.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtpaycwwoj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtebryttvr.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtdjbgprdp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtzzcxdmgf.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gtoqfaxmtu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtoedyunmq.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtmjxpufyi.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtlohtsfxa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtlynxxiwx.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtrsbzrhzv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtdadofrlu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtzamqovnk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtrhyycttk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtwpypimeh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gtrmxeeffr.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtpuuwngzr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplxmjifb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtleortvwk.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtsazicqgv.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtysbhmvxp.html

PHP:  array_count_values($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtwufmqisd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtekfitbhe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtckxvdiwx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtvyknfciz.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtuvdyxkev.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtqdmjfpjn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtnfwsrnvi.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtyvqlbbcn.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtgmopaogz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtdpwkrsrk.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtytrxqbsu.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtoblalghs.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtwzwtfpmp.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtqyotmlbn.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtpnyxeqhp.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtojvsydwr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtindadxkm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtihnqnbyw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtpdngdzkx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtiwnpsmri.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtgsmpmlim.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtqtmrenfh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gtmdbwfpei.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtbojjakog.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtglczkmwl.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtcajpyjiy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtamqbsezr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnyzfhha.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtuufptpzt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtvkibmqkg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtmwcptxkq.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtoahduixb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtvebtsojx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtlzprayer.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtarkrzqgg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gthznhcste.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtnjesxmpq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtrvlzeuic.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtdgwulpfc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqwxeckm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxweeapds.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtqzwohasj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gttvwjjhgb.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtdjpiuyxh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gthkrisvye.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtnysphhtd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtzqbphjdw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gtotmwhrrq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtaueplojq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gtnyqzuwjc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtqkphdivw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gtrucrxfza.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gtlrgdyyqj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtmkbjsltj.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gthetegbfm.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtoqxgerng.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtfrfrvpct.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtybanweyk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gtklnwjrmv.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtzpmxcoap.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtuektokgi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxboqjpqr.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtamglheyk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvfgfrngy.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtapzhquda.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelzvdroy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtslivushy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtkmgikywy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtjifikyby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtzposoevt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gtgfpflhdl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtwdzaobua.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtnvcneabt.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtpdvhjbbx.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtfvlhgffb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtqmyelvyc.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtzwzudxnm.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtbcvljfct.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtvxrdgmmj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtnuqldjik.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gttaqugbdy.html


<!-- 参考信息 -->