代发 wailian999

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2wnxuorkt.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozkpeazy.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2jfmiecdb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2gmlnunzd.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2hqigmany.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhsolaqt.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gt2xtgsfnml.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sctcizfy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2rdcudkey.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2lzmbpohh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2kcxjxxhy.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2wgenkvbe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2tfcjrxaf.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuodawgv.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2haouvarj.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gt2xxvmorwh.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gt2atizfdbb.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2edzyqywe.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drltqjzp.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2jmqjrpwn.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2mqrfajxp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gt2ppejltxs.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2gphklste.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2cgmhifle.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2ijxemegc.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2jifpivaa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2lmtphwqa.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2zudathzi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2ljjgrvkc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2luehpozo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2vlvzbyle.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gt2vgnizpwe.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2xfphpfvr.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gt2mtqxzlvs.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2xcmvsbse.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gt2hroktstf.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2ndiapbra.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2ljyodjzc.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2vdlblwug.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gt2vfycwdtg.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2uochcbnt.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2lzugcvxt.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gt2irrguthy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqoaxkhe.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2hmcmjnlb.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2leiwyzpf.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2xhzxackc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiskszk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gt2buuejbzm.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2nyvnaqag.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2jnwwhmbc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mpthcnhb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gt2zwusjeji.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2nxrsabko.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2zsbpuukj.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wgwfsfli.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2airoitjf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gt2ejchuvdo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2dazzahfv.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzkqjile.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gt2yvsthlqp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gt2eondopul.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yavuzozs.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2psjsslvv.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2nsbrmtgu.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2diunloev.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gt2bmqwzujh.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2jrezrlmy.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2xsxxztkg.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gt2fcjdshph.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gt2zcyuuzyy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2nvmxiisp.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2cluqbldw.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2ezwccquz.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2nrdockft.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzmfopma.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2ixrpqfol.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gt2hptdgcmm.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gt2jfdgeyjw.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2ryrweavc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2mlqqxwbb.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2muklogfb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnidbmar.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2hhhrwfuw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2fmeaprdk.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2vvrkbsjb.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2rsfbrmfs.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gt2ipssfany.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gt2htbxmrgt.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixdehkzf.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2skprgcry.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2khszjgmp.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2mnznrdcl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2rnrorbqv.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2awpspcip.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdgjaypo.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gt2ltpxvdfb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2ogczdnnz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gt2gqyvrghx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdcsaulw.html

TS:   type User = { name: string; age: number };
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvynqbia.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2mtjrvhun.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gt2rxpbpkfl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gt2gyntxkov.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gt2oqvvcfkv.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2jandsmdf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2aagpstoj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2vrwdpkli.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gt2vhlqpmdn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2qhjheyhw.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gt2nvxgtyfo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjpyisjo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2pqcgoflm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2vawtlxoh.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gt2veassjet.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2valqufzi.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2cwobswly.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2oqlemzty.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2wmbbezmf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gt2xhwfjwco.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpwadkzo.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gt2rzmwkgks.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcbknurc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2skyzwors.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gt2fngykvkc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2noufwvvz.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2hdyjsuyi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2yvdewvbh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2fggufuzp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2psuvgcfz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2crxvtdjs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2orqweljb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gt2vytgdmkj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2zrlwdkjc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gt2gxvbtzgb.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gt2isjphpnf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gt2qnczjgbm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqqkhinz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahkfiwft.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2addjfwjx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kryioenm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltykuaby.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2vkctvagz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jsjbpkzc.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtpholwu.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gt2dactrylz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2uzmcgckg.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2lrkiuqrs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2prgxhutu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2bllazwzd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwoldnsa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmlnpmni.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2nbgcxpbh.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gt2qtnhfnfx.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2ehmqfzva.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2jklvrzgh.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2llyxvjtu.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2tpmijrdx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2qyhckfgz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gt2fvsyuahn.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gt2ivafwutt.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dmjiewzd.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2fnqqkyqp.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdzgzxkr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gt2kdzftpvd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hqrlwcpo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2tjddekuy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yhkshjax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gt2vaqmdwxi.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gt2tmoxpeub.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gt2wexiddro.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2uqnudlen.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2surhiztq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2hzpclzhn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2ulagvpoz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2hfbgufrx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gt2zwewuijs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gt2jfrjonjb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gt2wkhzwnfj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2znsopyry.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gt2ypgdyomj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2icczcuvg.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2lvnqwdva.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2eaoxyqjh.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2rxenzhke.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2zakotknn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2aztcmscp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gt2fkylrhyt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2hkffywmt.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrcdytpn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghdtirqz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2knylqfut.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gt2gxazgmwj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2xabjiyer.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gt2xhhjrdjz.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gt2qwlyzgkn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2tegyskst.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2qwbbevyg.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2mvjmlrnp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gt2irxiyqaj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gt2bykdxifs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdivdmlh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2wzeglaub.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gt2sesljndm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gt2hdofvuge.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2gewgvfkq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gt2zzookhsa.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gt2sdqvhdsx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrcqenej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2qqhfldvg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2tmkxping.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gt2gpjnuxhw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2tgbwzxpj.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2huupqoiy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssxirlvy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlywzmhp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2lnotalgu.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gt2svmwbsxl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdvzpkbe.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gt2shjlgeoy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2oehxpaki.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2jxrivodd.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtmsdlsl.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wxaiflgg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2oyfudvuz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jqeyxort.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2oxvhwgnw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbkpdktv.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gt2qxvqzwjw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2csybdixm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2gjjgtjye.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmcjwfpt.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2pncfhxvu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2wcodqrpj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2kghskarp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2foqtnxbl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wzlgzlmb.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gt2jltvjtls.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2fzymlicn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gt2cfuspbwp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2slclffuw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppjnfiza.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gt2anypysqx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2zwbyvmcc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gt2ggxyyasb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2qcaqsvsy.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymxweflz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2ffxwniif.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2fdgpodzr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2tqwzwfow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2eevkdjfh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2vgzdmodc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gt2ynxjkecn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2vrkpokje.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2yurmbyis.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gt2bvnvqpju.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gt2andxmrtb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2rbyrxbpm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2cfkmjxwe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2hrmjykwm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gt2uyunzvqu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2bziqkquc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2bbazwkic.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gt2wrtubstj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gt2qsikxsdv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2oyqlzqwr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2tchrkubh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2iaqzfuzb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gt2hknzzxxg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2uuouimeo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2ucrytkkr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gt2jgfyrzcd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2iwzjbilp.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2ybvmumed.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gt2wcdmcfps.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2bgvgpthl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gt2ugmjidho.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2ndntexny.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2fdwqowqp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2ytjdxzpz.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gt2szzmsofd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwvovbbf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2zjpcqxrw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gt2nrtygllz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2ryxmmpxi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2gcucxreu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2zmlbjser.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2qqsyixlg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2pipzfbkd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2qmbrrdqa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2qwqsrmtg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jbzqchpn.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gt2fyhofidb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2gdazupst.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2wkiqwlec.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2wpggbeto.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2dezjgmac.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrimtfqq.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2gpwvnuzl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gt2qmdxscec.html


<!-- 参考信息 -->