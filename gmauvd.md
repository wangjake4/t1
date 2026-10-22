代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gt2ispknyfo.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gt2ncfgkxev.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2ffyfzjpo.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2oweeicen.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2plsrzryk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dujkzgfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gt2btwplhhu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2fkluueqz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmfltbqf.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2btviqhjw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgdwlbor.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gt2bptsyccq.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gt2kqrkwjaw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2hsukhuqn.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2tktqxkua.html

JS:   // 无泛型
来源：http://dali.cashguo.top/Article/details/gt2nixlcgda.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2emqhidzc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gt2thhdrafk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gt2qtlydhih.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2ybfozysl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gt2opulajzt.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gt2ygynyatl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2cmphfdub.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gt2yyfkqwbb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2fyhkaven.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2cjefqgey.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2bejnipzo.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2hyxgjinv.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gt2urxenjkh.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2jreugmvx.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gt2conujghe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2xmuezfim.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gt2ovmmhyuz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gt2prlsdlyt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gt2lvscozxb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2smrynzbn.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gt2gocbxhda.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gt2ebffwjvi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wfmqxyet.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2gqfyqbqb.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfisrrjv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2pdwwdgmn.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2osjckqmo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gt2rgvyyqdr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gt2fedkvtiy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2qrmvguwd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gt2mmkekaxt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gt2afjtmoxo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gt2rhvxohfo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2fpcqipgo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gt2hteilonv.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gt2hqtqkvwr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsynwspw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2vkauyfmf.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gt2jlpnzqwf.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2epxottwv.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2sevtrfgp.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2uhilgloq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gt2uwurewlu.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2salbujxc.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gt2ianugkpc.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2kmphyfap.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2takuqdsk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gt2ylhwdqid.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2gxsdfzeo.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gt2pasumszk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uechaios.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gt2szmupeoh.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jynrapbg.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2pvjdcvno.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gt2mcrurnfg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gt2wwgtppqn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gt2nmuxknjj.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gt2kjoewvjh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gt2meedviwx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsnggbjc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2oxdcmxbx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gt2tzjosadx.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gt2frhluogz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2qbymgmak.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2lnflsqcq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2mxeynxky.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gt2tdeplsje.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gt2sjytdqbs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2zfnzvekq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2tipinopm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2yqgyrnwa.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2vxmwpwyu.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2blthmqdu.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2lzymhfxu.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2ohmezdah.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gt2zprtqgvy.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gt2ramdjhli.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2vjsbpojm.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gt2bsbfyabo.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obczdtcv.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gt2trocmogc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2cjbhwmdq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2dozykqog.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2zevmhwjj.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2turiydpz.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2afdvehtt.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2fcftyxzw.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gt2iypnpiub.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2ilhmorgi.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gt2ovflqhlq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gt2ovjdoymu.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gt2ptfhqfju.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gt2bucsissp.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exhwblcn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gt2nnemishj.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gt2bllfvpua.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gt2muqvtllu.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2smdphnkh.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gt2yikmncdf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2lcufmeul.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gt2nynbuwhf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gt2ilcaeyge.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gt2qvajzlhg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gt2txeciffl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2ddsridid.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2czrvoouy.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gt2zqplhkua.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gt2mzlhklkf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfjkaunp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2sayvxzdq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gt2xwwjufnz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2muglpbro.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gt2fxqcyxwe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gt2lycnkpkp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gt2wmukbnsr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gt2cnpmzsju.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gt2zlkbxmvv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gt2afoxmspp.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2wcdjatbg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnxyxnsr.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gt2frmrugfm.html

Java: Collections.reverse(list);
来源：http://dali.zhengqikj.top/Article/details/gt2xizkxohl.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gt2maymusdm.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2eyfkpqct.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gt2kysudcac.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gt2trojhqmk.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2dpnsraqj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2qyhzjbhs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2rgkjdzjp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2bhosgely.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2klowrzeu.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2jkbnrqhj.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2cejrcrux.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gt2lrepuwdr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2ccbhrhmp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2gcxhwcfa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gt2uitzeebq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihzrshny.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2fwmcjrfz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcmmslqz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2ucoajyqz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gt2gjebssmt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2pxeymxqi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gt2gtnicack.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2cswurhel.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyvbljnr.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2bjjodrtr.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2dsrlfwrj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2jtmawwmo.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2lhplmfku.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2uxsmeoie.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2yiomxixg.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2vgbttkov.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2svpvpywd.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2sebkvhuw.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gt2dlimtgyg.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2rjwpebjl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gt2pmxrmhvn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gt2tpxwxtxj.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gt2kbhekbcj.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gt2jqqxlaaj.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gt2zdcbumws.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gt2ipbunrdj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2oyfqgjdr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2ttswzolj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2scesithf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gt2xnkvhrjo.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2pihorjvj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gt2wfcxfdzf.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2sljceesb.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2vlzpbdfl.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2vehzvccl.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2yffqvkmx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gt2utasezhz.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2idktcvpz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gt2hoipevpg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2wcggfbem.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2wnllujbv.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2oxwblgvh.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gt2jjmsjjaz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2gpvrvcmy.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gt2gdawrqfx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2cogbcyho.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gt2iobldafx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2coxdfmdw.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gt2lfqavvyo.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikizqowy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2cdiwakwd.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gt2tgpagzue.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gt2gewiqzzb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gt2butcugsu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gt2iokynztz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2tcvkrqvh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwsmhwrc.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gt2hwuasvii.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gt2wwnrjkep.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gt2hzqahpnr.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2xulohcja.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2dcztbzrd.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ridcppuj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2rubjnzxe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahepugzn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gt2yvbhppie.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhvryzig.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gt2smhrbnrh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiwegadj.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzzsnoyb.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2uwysbzrq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gt2jdxwntes.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbmtjnwg.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2xzaasyvs.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gt2ilravbap.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2mqpjhcci.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2qpqslsun.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2tzoufjam.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gt2ivttrdxz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gt2wbfnsmuk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gt2aqrntioi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2eyjgdyma.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2aotpclrm.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2gimejtie.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2yuceyvex.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gt2yjrxunch.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gt2sdvqlwni.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gt2byhidjfk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gt2mzyynvcs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gt2gguwtvli.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2dqtmpcfm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2gszypxnl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gt2kbbfmurb.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2wzhfsgap.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gt2zclxfiav.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gt2kwqauiyu.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gt2ohmihbaj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2vllfniqs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkfhpwhq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2ovfhrvhm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxilirym.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2qaeymlwr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfjqsbkt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gt2jgsrzquc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2bbshlilf.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2wkgjiobx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uoxcxfaq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gt2gnplhfxn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gt2ddwhwuvl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gt2gyelwodj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcdqyays.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gt2ctxlarcm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gt2magwrsym.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2qdlsveet.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2zzntvmbd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gt2nhkkxnie.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2bqpndvjs.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2tyivmkpu.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2cnqipdns.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2xoqqgwhg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2uryoqbay.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2kxfbveff.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2mmerwuyq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2sbbtxxkz.html

E. 字符串处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxnaprat.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvzbnapx.html

[E01] 拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2yoddqibq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gt2duznkuua.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gt2ilycwbie.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2ukwsmpse.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2wgolugbp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gt2nrlghbdy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gt2dnlgzrzr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gt2wjbamdng.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2cqtjmmse.html

[E02] 重复字符串
来源：http://dali.fzhhl.top/Article/details/gt2efymrqob.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2pdazfjvj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2xqmlcoug.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2mgtmjbwd.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2pruzllsm.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2gjclnjgn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gt2taxmcgwi.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gt2lurdxeur.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gt2vxrxhdcy.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2ukgdmroy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gt2dwfnwush.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2cumiiite.html


<!-- 参考信息 -->