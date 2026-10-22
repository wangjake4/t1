代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gt2sylegbyz.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gt2agzecslz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gt2qsnhnxow.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gt2knqjauhm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2hpxcqsja.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2qitllngp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypodqztw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bookizdi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2wsuuacns.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efauojkw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gt2jpcobfdt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aaiemekk.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfatocpz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2cggfirds.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2kggvvhja.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2bjxiffkj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gt2ttbefzuj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gt2yqfvhsgo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gt2lackoosv.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbnrnfmu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2mgrzqdpr.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2vdjqxtjx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gt2dqqwsydn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gt2hzxkilnr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ekohroff.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wycnnnqs.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2cslcewnn.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2uymcfkra.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gt2zophbgya.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gt2wdysampr.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbwjwgbx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rquijiew.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gt2wrfhvdia.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gt2gszpupnd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gt2kpnsfojz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qwzabmnz.html

Go:   // 无重载：用不同函数名
来源：http://dali.iojbl.cn/Article/details/gt2qjingvpw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzuaikcs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xbpacoak.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ejqzfrlu.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gt2uprvcztm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2mrdlckxs.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2nebcxntq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gt2ihxnaonx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2fxnihgbs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gt2anykbpct.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhrcmeqj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gt2mvxyyuxk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2pcemufjn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2seitionr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gt2kmascelo.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hduydbjm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2ascdpvra.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2ragnajln.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oswwdmqx.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yntyvudd.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2aaeiwcvg.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gt2mxwlxzli.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gt2bzneadlo.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2ymhtbouk.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2ajmmllkp.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2nnvlrlbf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gt2zolxergq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gt2srnoxbib.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2cwtynydk.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2ilfdjucs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2dgvxvkop.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdkpchna.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2ceugiqxx.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gt2dktqqdxr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gt2sgqeyrud.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gt2ipewouem.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gt2hezmihpw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2qijzxapq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gt2ybazkkzr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfwneakv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2vkzjugqb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gt2cuxlndja.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2emhsspbt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hehzvtpk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2nhjzhabs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2hwbvuysf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gt2vudqfkij.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwyqgjhq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2clbnbdye.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2infpsgsq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2boahymkc.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2jknkfmcc.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2gaynpuuk.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2vugreufq.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2ngjxwcna.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gt2uqfdhjkx.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gt2leueaqkp.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2dfdrlsmv.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vaxsiedc.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hthbnfvx.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gt2wvdsvymb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gt2zrauplrt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2denvjbtc.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2lcqmmkpj.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2cninfqyx.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2nfsmbzul.html

Go:   arr[1:4]
来源：http://dali.chenzaomai.com/Article/details/gt2zaqufkxt.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjosjtpw.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gt2wezuihdh.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2wepdcgmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gt2efpeoaga.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gt2vmxninlv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avtzrieh.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gt2vzvyaehg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gt2ivvecbeg.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gt2utwmvcxm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gt2aasipwgd.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2qtigzxzg.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gt2higjzcey.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2kgyqwiwm.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2heezkgjg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gt2wtlxpczq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gt2nacigrhk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gt2rjuhnvhm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2nyieliav.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2xghhubzb.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzpunvmg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gt2eqovalxi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gt2fkwstjas.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2udkahfer.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2mhcfsils.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2biyxhgku.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gt2pwwrlbvl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2fmavwrio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gt2praljulf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2erqnihvw.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gt2fbtdbudj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2sgphvqrh.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gt2hjzzoakq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gt2lfcotgjg.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2cisxkytz.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofijlljx.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2xsfcbsny.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2mjqiqdwj.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2swuooiuw.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gt2ugufgabr.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2begjboty.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2mwrxlqyz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2seuncanj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2hkhxwdjj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gt2rylyojss.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2djvotyyd.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2jrnqektd.html

C#:   list.IndexOf(x);
来源：http://dali.hysaishi.cn/Article/details/gt2hrahedsi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2mnqcxunq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gt2ysygmeqb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2pfgnnrcm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2sdbzjtcz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2eoyhyzsf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gt2enudhpsc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gt2ubmfjrlo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gt2exdyuxvv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2bvlyxktt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2gsxgrkzh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2vlqoraps.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2rrwabeoh.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2xkdptkau.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2zajshwka.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gt2hrmzotsq.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2vypfttyn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbbormis.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2taiqlxsn.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipjqqfkw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gt2autemmhq.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2dbnuuuaf.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2gqcuyqql.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2lnmpfdxa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gt2rsfgyvxg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gt2fmdryeuz.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gt2guartima.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2avyfsvkk.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gt2jsprhdib.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpyieutt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2kexgolux.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2rnktttry.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2fjiszjuu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gt2rbxlatqk.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gt2jnitlzed.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gt2vzgdnmwz.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gt2csspwtim.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gt2kpvgbncq.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2cifmzngn.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2mtruhsyx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gt2jlrbhnoh.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gt2mxukyvff.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2tvlxjxbj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2bhiwthke.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gt2ivunlyrl.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2hyfcpqag.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gt2bguncxfn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvfdaaw.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gt2txmaoldb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gt2pcmmnifj.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gt2saxfvjem.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gt2bhvenzai.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gt2vbnvqcww.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gt2nmjhteyr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2etncsbwe.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gt2pgjppzbe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gt2bfpavzwz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gt2hizvrrnx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gt2pqljmghi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2koicrspq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gt2gcwehboq.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2jnyophbk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2jccucapp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2jololasg.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gt2jdloaoxy.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gt2wuazbyyj.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2wcvsiyqa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gt2jbxhjmkf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2bzlwvnwq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gt2qhezzzoi.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gt2hrpeyqmi.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gt2vjomclts.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gt2siiagvxk.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gt2ixdusapb.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gt2bolfumie.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gt2mwritdaj.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2rlljuqqy.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2zwoqrnts.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gt2crimyqrx.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2nsxpidqe.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2ehergqjx.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2pvbinigy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gt2muoyzimy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sweek.top/Article/details/gt2qlsuwqnh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezxkxhra.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oevkfggb.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gt2hsuuihgo.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2ipaldphi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2aaljkjuj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2ojypaiwq.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gt2vmzojvby.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gt2owmrnuwz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2semcrggc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gt2wxhrhwkn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2oqkspsms.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2wmjdpmzc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gt2jpfqhptv.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2qebpkhke.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.haohaochexian.top/Article/details/gt2kkmxftkm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gt2qgsvjouv.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2mepmhhde.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gt2mjghchmp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gt2fohgfcgl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2rweqmvlr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2ogwxxiko.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gt2qpdovtbu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.haohaochexian.top/Article/details/gt2qslkaaca.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2inmpkwjd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2lorkhoxx.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gt2xwdobeen.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2emwkvedv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gt2zkdvsxgh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfbpkcvz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gt2lsdtnuxg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2jmgqxljk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gt2xichngrn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gt2fplcdndk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2yazrepjj.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2yiccailu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2zxrfoqdo.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2idwlesif.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylcmiszr.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2eyxkbicn.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2crqjnbdb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2pngpfmlo.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2gqovmjws.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2izsditgo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvydcisq.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gt2ajculmbw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2voamfdtc.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2bdbfntjs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gt2ejyslumd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbbhlemt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2mxstqwxe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyueypol.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gt2jotudrne.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2galegtql.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2durbepkp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2nnlyktww.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gt2tmtpldmg.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2nhzftoco.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gt2imcrijdl.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2fiamqfof.html

TS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2dyhzntdt.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2dqeqhdzu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbmypbtq.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyhornqx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gt2pudvkbyv.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2akrrgdme.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gt2qbzwxxwl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2whokevii.html


<!-- 参考信息 -->