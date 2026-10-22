代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gt2pkiuwtaw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2ptchqnav.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gt2fwntvcdj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpexwape.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gt2zmvrcxeu.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2qgtavqpc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2jvwcnywn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gt2lmczhhms.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gt2vnyexcee.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2omstkuac.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gt2izwrjpzy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrdnuujh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2bqnyqmdj.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gt2xkofvrwm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2wfrbngod.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gt2fdpkzwrq.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gt2axywjwrg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2qhvlpurc.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrgvkhea.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2mattfahw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gt2osyingrq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgrxraqh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2gtxljfgx.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2xeqdwodq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2rpbjolxb.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gt2ysomagbz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugmprtwf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gt2xcujgeaz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfgckxvt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ytpdneyy.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2hbwkyywg.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2qksbmsbn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsxcaaq.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gt2shtnvwxl.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gt2zoesafnh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gt2obwpbdwy.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gt2tkvuqplx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gt2ujozqmzk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gt2prufymjw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gt2cbsreupi.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gt2dztnfxui.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gt2dedmouid.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gt2wdgfbmgl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2eufiajgc.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gt2jnhxqbea.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2atjpubrs.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gt2erqkxnuh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gt2nvbuemkg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2pxcvthkl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2cqaxrfho.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gt2jqoegujg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gt2gnguznmk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gt2eywtunti.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2vtbccywu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gt2knmoolnx.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gt2znarsguz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gt2aqhromew.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kejplmqv.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrugiuor.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2lxdttiqe.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2evmdfkwt.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2icxgdduy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gt2jitgyhqr.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gt2jpetptae.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gt2qrrxqfof.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2oibxmgcg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gt2rzcbgecm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gt2zjuimuwp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2zqxoxsvu.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2rongbcpv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2rhvusdgm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gt2iwtckkdi.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2sgcogjnh.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gt2ccvvlkzk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxlmcsz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gt2zmqiuuhr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gt2qjnvujib.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gt2uzdfolsg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gt2sjavjapl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gt2foqlakua.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gt2ulhpxhso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gt2pxbqwvex.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gt2tbztxlbg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2sktmaqzw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2redxacjf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2oaazezla.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gt2tzkxqumu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gt2rvempqtm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2aixemayq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2siajpktq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2gjkbctvs.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2gbkebvtx.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2hflbuqki.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2lwyrkvik.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2qfjmwpno.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2exezyykz.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzylesgs.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2qhoalcbi.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gt2ikixbybk.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gt2ttvkdpvl.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2kxebhgfx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2imsjzwrc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2urbjblrf.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2lcreewqy.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2snxexrbv.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2ztmrmgdk.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gt2yxbmxrie.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gt2dytqqsjg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2chmzhusq.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gt2dudxzghk.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2siizgskx.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gt2iegnoato.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hysaishi.cn/Article/details/gt2vvdiezms.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gt2rtpjzjlh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2enyhywzy.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gt2blwogqru.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gt2olnmzkrd.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2wtpghuzs.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gljkokcx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2hyvrivbn.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gt2xuredfvt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2eqgvbxqe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlezuxlm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gt2wizrpqdu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2jaeqwefk.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2znsdqokc.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gt2evtnozdz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gt2iidxautu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gt2ykhtsbwz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gt2wypiqygk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2rzyfsfqn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2iiyhajnv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gt2tmsbkger.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gt2rlkksvue.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gt2oocqmbeu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2yxykusao.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gt2ogemmhvd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2cezyvquu.html

PHP:  array_reverse($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2nuxruyfg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voazqtkv.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2debtgrbm.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlmksrze.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2clscxtky.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gt2fexmwcli.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gt2rsrpfoob.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2wpnzbtdq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2oovmmwht.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvilchnb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2rwfwhasa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2wrlbowhc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gt2bcmjphva.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2suscbyfp.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2mmaodqlf.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2swzfiegb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdovhqmf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2klufdqkq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcqsiysk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2jtaqznja.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gt2pcudokdw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2pgjvdjjv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkjtgaup.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hshpfpkk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2hgqzlmgz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gt2xwbrtswj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gt2ajyaoolf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gt2wkvfrrci.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2eikwyojj.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2kakmzwub.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gt2xqshvatx.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gt2lejydasn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2oolrfydm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvelyvb.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2nynroyiq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2pghwzpkj.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gt2pbfqanqg.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2mtfhtjjc.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2rrptwdqq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gt2bpdpswnd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gt2oilstdbl.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gt2dupccako.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gt2llpncsuv.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gt2qleufkqv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2paktbfds.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2skowxpfh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2xefjxlbi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2ukrjyscg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gt2nabwevqe.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gt2tckwruoc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tianlin.xyz/Article/details/gt2ukfpfhrq.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2dunywtto.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gt2aohfyqtt.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2bzxanhwv.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gt2dgunjuxq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhsovveu.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gt2ryxihbfv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gt2voomxvoi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2sequtclh.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gt2fxwzjpvd.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gt2sdfccpbe.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nebortmj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gt2zelmhzgb.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2kxjnequh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gt2eleqhazz.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2zzqbsazu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2wahzcrvg.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gt2ejwrmiwq.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gt2mtqrxmqy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj202588.top/Article/details/gt2pumbsess.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwdcuekr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gt2wicyyghx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2okxuxwgp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gt2nzjnvtas.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gt2zqukgnzx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gt2jsyzmukw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdwuwqkq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gt2abnukaqy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gt2cboiwfmp.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odwxxzxn.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2fuqrecgl.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gt2ciidswep.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2hbhfgwlm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2hfqxfxmw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gt2hyqjzqsr.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gt2gchrpaad.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gt2wuossero.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gt2zataybrr.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gt2dqnvekzs.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2txiimxcd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrcnptq.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2nfhmspas.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2vivmfqpo.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2fanqfdaq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2vpzsrtdg.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2mcnngeps.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2nextpwlv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gt2vghjiaie.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2hhilkhor.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gt2epqqasab.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aeyagbpz.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gt2wstolsgt.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2zqcwywfa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gt2ygidjiwt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gt2xcodyevv.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2qtaligom.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gt2bhvydhbc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzsbpiot.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyemzwxi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2iqduljsq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2xsecwxzu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2xngptcnx.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2arerxdng.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gt2kgsajvbh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpbwpurl.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2toryuilh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gt2lyghcpjj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2rdhuthos.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2ynydxdzj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2imttainp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2qqcnwcfy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gt2tuctqovw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gt2hcfhrxbf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.birdmap.top/Article/details/gt2phxqqypp.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gt2zoojkbtk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsnjppku.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxixsvji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2qgvvtqiy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihpdskai.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2febyajse.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gt2wxpadqqz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gt2habmzbvz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gt2shjlrrem.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2choffnjb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gt2qdjdubci.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2papmsjon.html

JS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2gqcmiirh.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2ptjlbwpl.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2hrsqmppb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2chdtvrju.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrxcuysz.html

C#:   string.Join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2vmqronwg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2btqirhab.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2hbfnwcaj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avgxyyck.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2irguwlkw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gt2irdvsjxu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gt2trohdddu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gt2wrvomylk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2joghfwnu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gt2oxzcvdyg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gt2rxggllgy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gt2rbdlcrqe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gt2kjvewdgj.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gt2mtnuzugj.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2siluroxt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gt2cpgenfqv.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2fgstvkwz.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2pyrtrbvz.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2sdxsjrdr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gt2txzipleg.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2lqxrwdki.html


<!-- 参考信息 -->