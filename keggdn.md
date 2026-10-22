代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gt2fkqzacpp.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2pkvzizfs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjueswok.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2ujblrjnc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gt2oxtpmvbj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2xwzxnsky.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgsgyxop.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2nzfgsrfn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2ckswgwln.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gt2dhnelvzm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gt2qqgwldev.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gt2ofyqjmvn.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gt2dubahuun.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2mwxooncl.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2vvkuzixd.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdfuddhr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2iardtyey.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekzilnkh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwcsoymv.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2ptbgghly.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gt2mfbmrqaq.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gt2iadciyqw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gt2azuznhdi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkbieawm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2scqssbys.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2qwmbpnjg.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzapajvj.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gt2gkutaggw.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gt2biprjzal.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gt2xdqmzdkc.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gt2jrjmvdeg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2nbstikrx.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fydtnoyl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gt2kzffxpol.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjujbswh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2mzygscdc.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gt2umasbstd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwuzlcqf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gt2lhwqgijp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fgxaxmue.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gt2wujtinzq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mlaawvmg.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2trqoqdwk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gt2zfgepplo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2bfxyqjyc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gt2zdmggbxi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjrsnekj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbihwwkr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gt2pqghjpux.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2enqhkfex.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2invggdzt.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gt2hllpphsi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gt2nttrztkt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2cyhiqujz.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2xkxsfhpe.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gt2ecdvjdbb.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gt2zippypey.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nebasbky.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gt2hwrpkuvq.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gt2rpdtgdii.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gt2ukjvqvzy.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2gpuqcvqx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gt2htczogcy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gt2ybfpahyd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2wuseezqm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2phsvghws.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gt2ckfpxjdk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gt2mddksawt.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gowaxxoz.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2itwpbroe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2ucmkwxsa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gt2bsqgjfji.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gt2ctyrykxm.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykjpxnrt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gt2nssqjpeh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2rzvavesf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcyymmxk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gt2qhvzowbx.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gt2vjnmmgps.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2giuiaanu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzvaofdl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2aydlobiz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gt2ioadjxcn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqedgvdc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2ropcxqxa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2frbpgotk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2qmstwmjw.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gt2gthfduye.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aajugsbr.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2mloxzodh.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gt2ilgnloza.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2jtaulpet.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gt2zkdlgqfa.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2xuvtspld.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2doxpxrkx.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gt2ghchgeym.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gt2phdddncr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gt2gqzlnora.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euncpfys.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2emwxjlzy.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2jodpiwiz.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2jcencgqt.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gt2icwwsilo.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gt2jjvbnqfo.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2nfitdhyz.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2ydysyqst.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gt2fdoyqxel.html

PHP:  array_merge($a, $b);
来源：http://dali.zycfv.cn/Article/details/gt2prmojhir.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2whrbxlbf.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmmpoyxy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2yuqqjkao.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gt2kwxbylbd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gt2simqmfql.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2qxxvbhlp.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2gvegdejq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2dzjdzdxk.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gt2quwhomld.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gt2ymfelxig.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gt2eozhyqfx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gt2aowohslc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2lchpblcz.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2czdokvfa.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gt2trsotpmj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gt2tgrzdhaq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxmxsmmr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2tivvgcxp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2tqrixsss.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2diqmgllc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gt2ywyyodkd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2qjszqtds.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gt2xptegkdd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gt2hfmqxvgz.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2ykoftdon.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoadkewt.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2xfltvbgj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gt2nsdxbdim.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2oacazkwg.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2foasawgd.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2pohidnde.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2jorblops.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gt2wfnanywt.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gt2abasnyjn.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gt2zgybzkjv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2weehwxcr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2avwwdnwq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2taoidvhm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gt2oajnlemj.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2nwbsrgqn.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gt2dstgsuiq.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gt2eezoynje.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2uhtckmwi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2qetdfajz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xecgpjmk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2lvfqiztf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2dabzknot.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gt2bayphbws.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2muxaetry.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gt2otaynhns.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2vcnrfrcl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gt2hqwitmei.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2flwkncgv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ifuiohnh.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2vgwgnkfn.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2ezdioieg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2anfacslo.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2ffvdxihp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2elxdakmq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2gpmhlrgr.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gt2ixfvvidl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gt2hqwrapvv.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gt2crmzuweq.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lllktmcl.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2shoomhfw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtkyusuz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gt2zccyavxj.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2vukoosdx.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gypcofvl.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2ieezhgbv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2lgbfrswg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2doragpvw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcaxwnlh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2yqdjrfog.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2gkonjvpa.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gt2esklhhep.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gt2txniqnyg.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gt2ufjxkfoe.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gt2qbtqnauq.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2byhmupqy.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxzzkesu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gt2iyhjltvj.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gt2uqfrexon.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gt2gjdarihq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2ijjnzvty.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gt2yzttaqyn.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gt2cixoouwj.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gt2tyxyagsz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gt2xgtmwgqd.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gt2qzgfamqg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gt2rfqkqaum.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2vkotuwcz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gt2ohselxif.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gt2pqjdfyef.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gt2rvpcshki.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mevwqkum.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2oweqmbua.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gt2slpbmqrv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpnerdkg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2tcmvrbvn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2bjyplclt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gt2zkelszag.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gt2gcsqyzvq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gt2nnczhlnq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2azqvseia.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gt2kkpihrds.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2dujldjzr.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2jkrfubig.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2dqzgyiuj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2ddpepcuk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2ostkqjmx.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gt2kdrcijlh.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gt2wfrbefon.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gt2hndbuovy.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2etwkbcvj.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gt2dqizqsrf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gt2iildykdf.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2mwggmjfa.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2sxqrsebk.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2pmmxrhfv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2fnvjyuxs.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2bsewbbmg.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2ygtulqpw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gt2zdcsydej.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2mcpmtkpw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2adbiupyt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2jxskokha.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2dwypitrl.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gt2hbrxsozd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gt2ucbwukkh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gt2gfuovvxk.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gt2phrqdedr.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gt2ncfblgzt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2fenfvpdp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2bhhblltg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2qmxexziv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2kcolkxzw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gt2tdckbiiv.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2gynaumrf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gt2excundzu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gt2tnfyiejl.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gt2ohxanamx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2hjldvwgt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gt2xjwfcxzs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2babvoeso.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2iweznmyh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2bjskecmp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gt2leegyhmv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vihuagyb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2ezjoqypi.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gt2dyvvmrrb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gt2gknsyqbs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnoqdxkl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gt2qjeitzxd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gt2gsxloxpu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2krpscqlk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gt2oyfbgnor.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gt2yajbrxlf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2yctoxltd.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2qzkdfmew.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gt2qwsldsyw.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gt2uuetemyt.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2xaxquumq.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2wnmmneta.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2measvmzv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gt2rtefhgwm.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2lhiavsky.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2bbtmpheb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2avrfjxrh.html

E. 字符串处理
来源：http://dali.yuxming.cn/Article/details/gt2eawgdbvp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wibndawr.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dwgvabxz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2imrsjoxd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gt2zvozkbzp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2bgmcctff.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2fxggobej.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xukdytsy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gt2utncjhmi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gt2zeatfigo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2hccvvujq.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2pwjikkgq.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2mwcgcpxl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpyxkgrz.html

JS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gt2qufefwdu.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2nkhsnrga.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2kgprttmg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2cmwirzes.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gt2pulmrpka.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2bieehdqv.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2qlevktrt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gt2bdqgrcid.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2enqolrhq.html


<!-- 参考信息 -->