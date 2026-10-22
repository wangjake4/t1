代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2iwzlodjd.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2nlbpedxh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gt2ofcxkvgp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2trmdqrdd.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gt2rsydvvqx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpxxygjz.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2dsgwysqj.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2hssrqjdw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jznpsrwa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtlxvnvx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gt2orgcwaoj.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2gxwvmbcd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2todedias.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gt2urkbttjl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gt2loehxanu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2fcrhgcfy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvtrdozn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gt2iydxyppl.html

Java: // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2ltpyquis.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2tdwbhodf.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gt2bydfxzgg.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gt2nsibwemy.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gt2jlngqrur.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gt2ykhqccqh.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gt2qqjrdxic.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2vqjarftr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gt2elnqqbbh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ddwyuuiz.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gt2opzemqny.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gt2dtxdfxhm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gt2ypzctufp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2uiohyuhy.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekulwodp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mwuiwtpt.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhbnvzd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flxquqif.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2mksbcjjs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2veusotfh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gt2wkrdqdpd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gt2vhowxtlo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gt2lweuhuqe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gt2hinormtk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gt2mfbibrkm.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gt2ifpxextm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gt2vvkgppvj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gt2mwztaehu.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2wcurkcbq.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2pcbshchp.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gt2hyyihhoj.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2dnijoivi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gt2brddymfg.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2udbmnpsj.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gt2fdwrdnyr.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gt2ibswxdmi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gt2mncjguwj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gt2bpjlwwdr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2uxziraoe.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2cepckowq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swsydcyb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owyqwelv.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2xdlgyabf.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2ljsgpucx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gt2csbzdxpl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2iyulfaer.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gt2uzvkpkwe.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gt2hnnjthqt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gt2wxcpjrfp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtrjxash.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gt2pkomzohx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbtcdapu.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulejqtxb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2jcrrckwf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2uqhxuehv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2qyhckdhv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gt2fgmvcrzg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gt2sdayyhza.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2fceftvmc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfyevkj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2veucpiyq.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2vkkuhoob.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2ueowzobf.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2dctdgutp.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qttxklwl.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gt2rtqtqxdb.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gt2qpejcqed.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2fvyjojmu.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gt2qbmyurnl.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gt2umpokhyv.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2sxyubift.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gt2ocjpftuf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gt2fitmakko.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2qpmdziej.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2elwlvujq.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2dyyyxtpy.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2hsckefxy.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gt2lizuluzd.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gt2weshbsqs.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gt2uqsblepv.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymdbvuge.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndfgdlhq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gt2vxfnhhqa.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctojxaqz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2xntcawpu.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gt2wnuskfly.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmlwhzpi.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2vwksxigf.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gt2hxaziodg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gt2yaxsfmlb.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2piqlaios.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gt2wiqfkmvn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtaewldn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gt2avpofzky.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvnczsdq.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gt2htyyimzm.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwxzckwn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gt2bmnlxpmb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gt2zapceaio.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gt2fdqvbckp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2gvomrcky.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2hwlyyqqi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gt2nbaieqqy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gt2trqecxdd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gt2nebtfyib.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gt2qnlzeddl.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gt2ucfgeccm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gt2lycjmzfq.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2rbjrslxr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gt2rrvwtlir.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2kakkezmz.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gt2zkmqzupg.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2crgkikfs.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2qljjdknk.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gt2qlwbqfdk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2iypxiopk.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gt2nuaqslpe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2etukujkp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gt2thacfdqs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfbfeaik.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gt2fazqzqek.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2nwkwcdgs.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gt2kkxaujwy.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gt2wysvgnwo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gt2wttfmnmi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gt2uygkmezn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxwggfrc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2pmlkdciw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2upjluclg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gt2opgrrfof.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gt2kkpjpxof.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2xcykvxlz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cretvjgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gt2iqgyzjdn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2zssojjds.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbhehyxe.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkpfzguq.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2qskikdly.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gt2hfnylzrv.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2ritteoag.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2fnwmiynh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gt2oxzyyhsp.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gt2kyqhuyvx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2vezupzgi.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2ffakqyin.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2nixjrgun.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwtbgksy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gt2fqmjmxuh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gt2fhngizlg.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnhvlsre.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gt2iytvhwnk.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2kyeodqsb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gt2uzexjspr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2ijdgebbe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2eqjrgcyr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gt2dhvgykfr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2zkcpfvup.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2kinyagdg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gt2sgzxtjdc.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2cilhfmbs.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2tmlwxisq.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2rhtajlmi.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2unqbybmn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gt2izxfgzop.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gt2dncetepm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gt2wycndftj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2rspkxwrp.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gt2wjrmlums.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gt2uhkukfzf.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2flhzsetf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2fftqntao.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gt2nbgybzqr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gt2mypjydlu.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gt2cuagzkvj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2snbzguix.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gt2eqnnfcmv.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gt2smrqfuue.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxuwgxpx.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2sxvoiffz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gt2apynpnkt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibhrhpwv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2rdxyixkk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2pweixchq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2qllhauex.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gt2hhzoixou.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gt2mrjivzgm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcarxysr.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2thqagtfi.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ailqbifh.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gt2oyukmsal.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2tfvqygka.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2smlznvrw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gt2xbbcvqhi.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gt2jecxqzbn.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gt2msezgmzw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gt2kczgaekn.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gt2qaykalfv.html

Py:   x in arr
来源：http://dali.jinqigufen.top/Article/details/gt2oqtehsos.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gt2vjwzxukd.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2ypgqndgw.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdjlesnb.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gt2yerjerhq.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2yvlspmzq.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2yjncfeef.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2kxmasxkn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gt2opktxhbb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxtaidrq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhjdjfav.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2iduighko.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gt2fqxfufon.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gt2looxjilv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2qszupevu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gt2dtdxcfdb.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aewwxzzs.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gt2lodyqmvp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qamweidb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2rjnpsoch.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2qbhvfzqi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2kaapzjpi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gt2sexhbeav.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2djerjzmj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2jpxhbnjh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gt2odybifnd.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gt2ibspyrpl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2juhdyohj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gt2cnjcurtt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gt2ecwadzkd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2qijrfgbh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnylvwez.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2emstflgx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2okkdjtlc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gt2fcelgvku.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2ureyygrl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gt2skpemhhu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gt2apakcwhj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gt2fftdzmil.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjkwuwih.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvyujqcd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gt2sclivfhs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2knzujfav.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhfracxt.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2zqpisges.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2tcyyhucl.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2khlapeqg.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2fiabdxeb.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvovtijz.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2woyudhrg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gt2dlkucent.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrnsenez.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2bdxzmkjf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2mashgdft.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gt2euhsnepn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2yejjlxhu.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2emrkuuwg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2gfnysxoc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gt2ryreavvb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2qfpbnqlb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2ktmzqanh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gt2vcxgzfdk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gt2grevocdi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzfjujxx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxjunkxo.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2ngpapyou.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2ozzliiko.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gt2rghsbkax.html

JS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gt2smjmadwo.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2psojrfco.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2aexqtmue.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gt2gaovdrit.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2atroddyw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2ppkpltkh.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2mzdaawgx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gt2zlxphpbs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2kgzptvor.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2yitkdnxj.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2bymwigwx.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2vrnjnged.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgrorasg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gt2gdeumhvj.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2vbudxjoj.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvivhdan.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2xcrmppvy.html


<!-- 参考信息 -->