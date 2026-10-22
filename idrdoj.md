代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtlihhclwa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtoflkgdhs.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtiupjxbti.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gttwmjfqmp.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtjywkaqju.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gthtaayslt.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gthkyalvpf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtmvidekim.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtrvufsuej.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtbvscyzbz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtlttrrcod.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteadtbire.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtanajvybf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtobvxdovj.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtberczpls.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gthpspclnv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtztacdqqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtnkzbjbxo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtufijyzop.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtmqbaptlb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtdalzrfbt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtpuaysgce.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtsvxmkxtp.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gteexlvylq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtctzouktv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtcmmonobo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtcvzxhvnd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtwsskmvao.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtwnvgzwfa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gteayygswj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtptemxruy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtbmsywtyp.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtvjnhllsu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtzsjtncfj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtzvkpcrqq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtxhnzoapm.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtzfoqepqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtshlufbhx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtatvadtjf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gturmrwesb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtvnoadkji.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtekgomumc.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtreuvrftm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtnbbmrtij.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtcqwtssqc.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtrdryophm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtvcribkdq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtqnhenpze.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtfvecxrpx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtsjimwxsv.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtinamujyg.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdxyfbrv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtrthrsepa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gthairafeu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtipyfgbpn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtmanyjabe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtlqiltymx.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtkrjahjxr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrngvfvka.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtfqxhdxcc.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtajpfuzju.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtmaueoczm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtpsjrtbwa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtpqmdyvyl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtscfrndeh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtegdioonu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtibokttrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtolujqxbx.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtlnfendkh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtwueqbpkx.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtlzyxhjzr.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtkwhrhdys.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtvbpfwiro.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtiooboimc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtuokmamux.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gtsxcvognk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtdcoucbtm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtsglqspro.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtnzqfupxo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtqobjpstt.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtweyepfbc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtdgkiwxbe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtjxtqtbhg.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtvllkfmej.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtolmjkesz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtpwuyiocg.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtgghnooxc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtayrjwphu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtfpgawdic.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtdeutdunw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtagtojvvy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtpvwgygtt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzkuushk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtrzpcykml.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtrnpxkypa.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gthigxtijs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtwtrwbide.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtdcxrtezy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtrxszvjgg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtuvbgzlxq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gtqtycoarw.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtuayevsby.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtwqagxnjt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtynpobrbw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfzpnwpmx.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtlcqvfikw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtldurzeep.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtclkcywyw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtzolwpnre.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtgcdgmztp.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtucyxkgqm.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtwglydabn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtjtfrykmc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtcdyspgmf.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtwpmzujiy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtykimmpaw.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtxmctgnpf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtvroclxti.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtivffbqsc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtgyjdhpkh.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtvelcsiiv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtpgqvnpju.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gthrughvvt.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtobfxqeab.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtbwllmxkd.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtyxxfpuhk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gtbziswaft.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtfjtzooiv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtzpzyvovn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gtuljryszy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtodwaquld.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gtvvhbdhyh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtoqgygwhj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtoxokigmj.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gtxsouiwuk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtqjupxfww.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtyqljyqoh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtgbeeuqrq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtwrcaaqra.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtjajgtgfv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdizxzzo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gtymsdndzu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtdhjbbzui.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtxowvhgwf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtnibxspup.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtqfparcnf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtlcyikyoa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtqfkmwfgy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gtvmgyhaed.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtfdcuzbrs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtqxfzoehk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtgumrulfc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gtmkpqkvke.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtwcyltxdq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gtduzufgna.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtvrkzfkzm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtrjopqrnf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtecqwwsby.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gttfdsabnd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtljhfbebr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtmbyrrvyc.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtwkgjbpio.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gtxewtmmyq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtnzizqtmw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.havefunace.top/Article/details/gtmikbqbyh.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtxrqbgwus.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtssiakmlm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtnrulvvpd.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gtilbrrauk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtsdkhlzjq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtowhdbjav.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gteytdkcva.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtypbypyxz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtkdoxanmg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtaoygzcak.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gthtucfehc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtyonapqcc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtwyzouoaq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gttutceuiq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcrkdwcfb.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtheldarku.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtosqukujf.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtsxatnwps.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnfzsfpb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtwqfbocwc.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtjsrmprwu.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtopgcifwc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtaofkmonv.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtjkzyfrsg.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtfcqryara.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtlqfgdrcd.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtqinjehyj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtddfidyed.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtlbmcadyo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtweeoxrko.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtecuezswl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyltjatg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gterfesuwv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtmxgglgbu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtrgojatln.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtcsinsogy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gtyjkvwdga.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gttfdwolrl.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtdjodnfgd.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtiegvnosk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtgolualgn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtvxxgpsjd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtenjfazng.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtgmhswlqo.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtjawdimub.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtmipygxcn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktyzbtrx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtirnsvjqr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtrkbflljg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtjndruwpi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtgxbogjnw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtpcdpnnag.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtamktdnqw.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtualkxpgn.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtnhftkyza.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtrbzwglia.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtowvvyqwz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtkmxylzdw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtirxabvlr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtbqemicvn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtvigkrhdf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtwcrrmldh.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzghlrfpg.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfobrschv.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtgyjljzdj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtkxrakdcx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtzoawlmsc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtjpczuuko.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtfcowphid.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtpivqljnt.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtgznhsecd.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtjvmdefeh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtucsxpdxb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtgzoqyhbv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecuitjkd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtmpbzetce.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfezpztw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtvlmxsujg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtitfbngio.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtaujtgsmr.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsazmrktd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtvwyvudaf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtptdotbod.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtymdaxxlk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtpuobgqpj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gtxdasrtpd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtuddjlqvj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtbpnqzbsa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtbaaaghcf.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gtrolazqlq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtawykteyr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtfjtisnvb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtvxijmxtw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtijccvizm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtmmbikxuw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtlaxqlzec.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtotlsjfro.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtnsthfkse.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtrmquxina.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtaqnxevab.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtftaulggh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtdyqdpdiu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtdgsjxnus.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gtdjoeclax.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtntrcbwav.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtpflrxzjo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtbjajdoxc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtynncdtve.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtcvtezmgn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxohjwwcw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtzyironlx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtuyqwccjs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtpmjzwock.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gthvwjueia.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtugpqwxrb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtfuutyopk.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtmiebiesp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtjipsohjl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gthlmhcian.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtyyqstqvu.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtcppzegoo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gthekjweir.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtgznctujb.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtgrpxbrhz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtcgguwbkw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtqkhimroz.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlzkysvs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gtkewefsdp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gtomdftsyi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtxyrwhngw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtzytgpysu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtjakahgjm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gteomrnmjb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtfrnwxrhw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtqvyzdemp.html


<!-- 参考信息 -->