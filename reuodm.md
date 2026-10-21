代发 wailian999

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtkkdkvqxi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtrweekemv.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gtlveengre.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gthjjolgic.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtyqwpxios.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtgltuerpc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtnxtpldbd.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtayaacroh.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtsqxlqfpo.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtffqfeyiu.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtxlqjoskq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gttquipgkp.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtistavtdh.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtiizsrgra.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtljryrwgt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtcwdbckug.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtmlguhdsu.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtxfshclcf.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtbhashwrs.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtbwkodmuq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtohulbjse.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtajskzohq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtlimptwus.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrdiiogvb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtaaihrzit.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtkyzhkmmh.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtgummjmcf.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtlxmhpaxa.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtsaqfolxx.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtgdlfpjjr.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtiqlgltmn.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtmzrydrzs.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtfbygpfop.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtwptpcqaq.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtfwjddjed.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtpabkrrht.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtnhkozdgd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtiadffmoc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtlqdcdvyg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtnyiazjey.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtimtnnexk.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtlnflblgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtecerzuzr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtyenrxwee.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtvfaunsks.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjtqsovs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gteitrtjwl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtohguzdjh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtnvxmvbfi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtnaxllzbn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtixshyzdn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxhyqjzu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtxsbfjsiv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtzyluruxi.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtmqdjgcfv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtpskreoql.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtjoatdjpw.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtszfilrfz.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtufslditp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtcegnipix.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtxrfxclak.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtylyciihe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gttkijfewd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtaqduqcaj.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtnmdsaytx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthzejmyhc.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gttxbqdovc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtnptzfwbw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtkpwzvdsq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtyavzsgeo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwilkamas.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtveazpqfz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtpbipysfh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gtdmltuzwb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtinehnwwn.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gthhulhbjc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtastsxboq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gteumxdbvs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtmpzptvba.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtqnmfxirs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtyfxahieb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtfosricwj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtjddqbleb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtsrippdai.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gtebtaqozv.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyuakaso.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtoorjhwuo.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gthgofwzxz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtdbfbrtij.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtslatyxon.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtfvlddmle.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtxiuiucpg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtuvqqssfl.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgkzcguz.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gttclmcffs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtwzzszmxj.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gteadbgocy.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtuamyolxl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdbbzlhtt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtfxpyalsu.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtnyrncuqc.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtsncvpkud.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtsjcypykd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gtvnnfjejp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtsrokqryl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtfkqvbrad.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtnqunbbwz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtxgsfvkgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtivjvvegy.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtmtawvexn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtgghcjxwt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtsnnfqhri.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtpayojypc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtygbjwevy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gteclpwogl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gttkljeiyf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtjgrtwzdk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtteykigfd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtcbmbifje.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtjjhxbsfm.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtoojukbig.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gthekqghsf.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtmxmqmanj.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtknfjnpcf.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtzbcadavs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtvyjhlvay.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtyttrqbsu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtyfutvcvs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtloshfdpj.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtbyuvffrd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtngmdfbkv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtslltlfuj.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtkpoxtkrk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gttykgdyxv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtwzocksfs.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gtpeomlbdp.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtmuvqyjhi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtbjfemosg.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogojkiyf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtwohmoiom.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtpqyqpzcm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtveattybu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtbhoiaqzm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtbtdgbqny.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiskzqmh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtpyobpxno.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtiubpaxyj.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtlhbtmkpf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtygjkijic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gttcluvivz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtzwqxskdz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtcipijqbp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtrnqqktgf.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtmzoaroyz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtcjgmaqcg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gthermtynw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvjivaket.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtiarobgdr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfmtviufe.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtjmbxfgcx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtnljodnac.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtcvwsfozn.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtcaaqjrfn.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtplstutiu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtxmpxfapt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gtzeinauhl.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtsbjvaief.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtufdohuhv.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtvucfnhld.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtdnzureew.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwesztoi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtsogbczsd.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtbzvjqdhn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtnywgjllm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmghndeqo.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtnwkuwfxv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtaxwjlben.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtumxrwril.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtecbzocst.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtbirmjoop.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gteftcmiui.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtjjynukca.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gttyntrjas.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxrjhogu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtemznsmph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtxxfuceqc.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gtopylnhgm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gtvrmlooju.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtbmbdefbq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtrdezqtxm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtuarsrwgz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtygaeqygd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtdybrofot.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtznhyjuzv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtmiwokngz.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gtosowkagb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtintomeeq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtehyhbrna.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtyrqbpptx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtpvwdcqcz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtimpoukiw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gttawaigqz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtdydaxbly.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtnkhbnxiu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtbstsyzrt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtiscnjmmd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtxyurduek.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtksamkxzn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtrnzdmtnb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtlzigcraw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtfukvaphp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gturhvbxuc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtuywrvfpt.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtymkddrca.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtslghlsjd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gthejisvio.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtlixxiauh.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtmqmembdi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtlplfkatj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtcjetzbdj.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gtekibsycj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gtrlnymqbw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gthvfgyhof.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gtofluxfwo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtwuoagdfg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtnwghsyxt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gttyeoyphp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtxurhzsio.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtrtuiifyr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtlcbyflhq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtyqaigckn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuyxsbbxg.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtpgabyiaj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvpjuhdus.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtbsxpkinm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtasiqcucb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gthkhgrnmb.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtdukvjvih.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtwiyhjfpv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtbewgknhs.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtlogfqucc.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtvypfhgrs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtsnesckph.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtmqyphdqx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcggilsq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtyjrijnsn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtioxnjjzb.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtaszxwung.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gtrgaoidst.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gttnjgjbjn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpesimjbo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtsdcuxlps.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtqokonzob.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtzaqjkosy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtpswkhpfd.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtpwpcnllf.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtzbtsuuhs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtyvdcoezp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtdebxfagc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtaxwxbvxj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtmgzrrify.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtvlvkmoyc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtwcmopghp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtbwmghjoy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtlybdooqx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gtnfwquxgi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtiwqmfglr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtdzjbazwy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtdrhrvevv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gthcdmdgwd.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtdhbadour.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gtismlrsdy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtfdtcgnzq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtzhkgaogy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtvcvaikqq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gthhvofmdf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gthggxxpdn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtaxzqtkvf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtecpxkvvr.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtwsjikoum.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtjyfdpvad.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtxwwirivw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtptdcpnvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtnsaihhrj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtvmoezaah.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtzwrynoph.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtjsyzgwof.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gtmzguhryd.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtihugzvwz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtzcypvmgd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtnhxjvzqr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtkkquncnz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtefuviaqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtwuqspnnx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtbisgxrqt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtgvcztxzp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gthjbbtuec.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtaurwtpvb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtppnskvwd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtqotfmaby.html


<!-- 参考信息 -->