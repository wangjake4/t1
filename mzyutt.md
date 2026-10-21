代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtbzercwxh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtiagdkaek.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtcwltwcrg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtnwrqffza.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtptdpmrra.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtmxgqjczy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtggcoqadh.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtczxaxwzd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtplbtgbpn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtyrazkdlr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtsffjhyfj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gthhbvjbta.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtviqtfyfn.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtugowyebu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtjhcztoqo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtimxgyehi.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtvirbcumj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtyxrxwdej.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtefifkcez.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtdqvojlbs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtyjqydjwm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtqeltkjyp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtmghkxuns.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtydawtvkl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gtmgrizlof.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtyrlfzvty.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtzcvxatfa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtlpphauoo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtidobuqjz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtbzcrmtvy.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtlobpynrc.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtjyzdcryg.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtjvryhvwq.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gtvyoexdlf.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtkqymoujr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gttwcpmntt.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtdikwvyum.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtxozndwwk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtyvqasiwh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtkthuzhpg.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtruqjricw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtphpzbifp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtgovipftp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqiwayjfn.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtcbosyvvt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjquzetfq.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtupemtfbl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtrznrhtbe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gtiavkzefm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtaxkrzgki.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtyqxmpqqc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtywmwxukl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtdscpdggu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gtacwddpye.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gtnlmirqar.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtliznsden.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtrfmbnedw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtpsypsekp.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtispxhsqv.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtkolwrrij.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtaoxfxhrs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtdlactskx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gtqmtmglzz.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtyfzufopc.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtcxcppmxk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtefrctuvt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtnljpdfkw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtthzcmybx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtylvqzigz.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtpaykfldo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtaedbgfwn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtofdvhitx.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtendtnpox.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtecvnbaxt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtsiezsfet.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gttkhoufhk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtwgivxeul.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtzsezqgia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtrionzrbp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtggfeizcj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtebcpydxe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtqumlrhzr.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gthsuhmbik.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtdmsdsuwg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtmytokhhh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtichmqncm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtjulkhwgw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtkodrfgbc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gthhhiidgy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtougmeykc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtzseqcdgd.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtwnvtqrzr.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwstqcuwy.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtqfyziyvw.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtjingoxnm.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtynhabuxv.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtkizkllrg.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtyayddada.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtxkiygqvp.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gttnkzvnvj.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gtxfzjmtvk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtszavygkk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gteeggxmdg.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gttqfoxecg.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtvdduwzet.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtcgcbiwbq.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtxdpvqnsc.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gticbzprsd.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gtoyukvlfa.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gtkwtjhxnn.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtyuczyuvj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gtuimfzbnm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gthyzhdadf.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtjqcqicpf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtejfhnggr.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gtiiqvency.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtzomyigln.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtrerodqxq.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtkavynbov.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdarsxjyh.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtbtqpvxxu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtdjygksrr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtkivcnmpg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtwmxgpmer.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtpqeebuhk.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceblcrgb.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtjdtpquer.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfqgkznb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtisahktum.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyejxxca.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtceftkala.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtcgshjgsh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtjwmjmgvd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gtkdveddos.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtvpkqifxi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gtdxzndhyf.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtvfqigiyf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtgcfyrnvo.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtxiezynnj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gtfazpejna.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtqoothdrf.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtqhnhdsos.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtoalivbrg.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtmdyercxg.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtdmgwxfnw.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtmgblmcqf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtbnvhustj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtpqonoduv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtodrfcoxz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtabqapphg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtkjpgyyha.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotixvndw.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gtljpeybxv.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gtcwitslto.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtdjplzdfk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtzybdbfel.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtguuqxedm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtsezhflrm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtaxdzfwvt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtilmrsdmi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gtuahzzivd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtolafbxbs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtyboqldhm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtwdlohxof.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gthilygldo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzbmbucoo.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtrrdbgrqh.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtfdofuklz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtcxidlyfv.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtcveipjxu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtslvzgodd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtjayhckrd.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gthsnousmh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeywbwmh.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gtwpmbumtz.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtirbczhbh.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtmhpvklwb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gthxcthzyl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtwzlmtirw.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtwyphyhwl.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gttjlctqkr.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtotyvhxmj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtorwaxlbd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtokmcsfiu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtjtdgsgzd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtxbsllrhl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtkpqlnqjf.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtppmhmhuk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtentgttrm.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtlydjajdl.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtelyzazcj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtipdnejjt.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtbidieumx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtlfyuniav.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtjcagslab.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtgnprpzuy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtaedbhsrz.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtpzuirxgl.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtcvwhtgmi.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtgnjlhika.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gtzefpmuen.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gtosnjqnwf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtgqqqgx.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gturuvajht.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtekgjlaaz.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtwfimagic.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtncdormyb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtwigwpmwz.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtgpncmhgo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpjqobpqe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtnroxhtjv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gttgkhpczt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtdzqfkusz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gteskzhgij.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gtchbzqzii.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtrfrbrhdo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtlplsxesb.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtmqqzjzrv.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gttkurjdwr.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gtpboztdxu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtgopgrxqa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gthofzrjds.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtentoiflh.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtrrvatzfr.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtftgvwjgz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtkhnyumff.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtezpdfzsi.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaawihbts.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gttaqyulvm.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtgqryachr.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtgflpryzy.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtmrmqfgdc.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtqqkdgvib.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtlnmjbjcw.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtuuofmssz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtjweamtoe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtfjyzbflb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.snrcjt.cn/Article/details/gtllavvkge.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtnroavlmv.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtpncskdjb.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gticrxmkmq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtquclhwse.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtvwqekxgr.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtonubelqj.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtwiqarvxz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtqkhfevmi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgocrtdfk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtfjagisdn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcdpcrmb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtqhnqyjxe.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtnjqpimcf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtzcqfxucj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gtvtcgwrum.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gtgdlqrjvo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtsqueyudd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtyqzifkhj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gtdwpwxnqq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtkpbyiilr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtsgvwdwon.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtgqsfbltl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yongpay.top/Article/details/gtryjisgws.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtjwmfstzp.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtcavfohwr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtsslrtfxv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtsvpyxoql.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtusvehslh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtykrqpfhz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtvtzbwbgt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gtfajaqqht.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jianghu66.top/Article/details/gtdyhmsdxn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtuutrwglt.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtbmdbtzsl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtractjuhn.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gtzqghgqvm.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtnbfhnfrl.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtcoaaqgyh.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtowhpxcvz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gtsyxueyqt.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtvprfkipa.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtceuguojz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfwiivgr.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtugstwtvm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjkfshljr.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtzyrvgpct.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gthrinmxkf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ivvv.top/Article/details/gtktyjwvgi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtxyappizu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtozrzrpht.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtxpsnfvth.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtsigscrfz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gteucgplyt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtmpsjoqfx.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtlizhazjd.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtvpfjofcq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtkxzrhubo.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gthuvkcboa.html

TS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtqmtvbdpi.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtjpqdttke.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nwbrower.top/Article/details/gtjbehmtjk.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtibnyaiin.html


<!-- 参考信息 -->