代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtjkttcpjg.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtsobiwciw.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtufyuurea.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtbfgowala.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtutkmkhfs.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtpxfcixnc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtnoqijvtk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgyyscflg.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gttzrbligs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrwqylstp.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtnmtbvewx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtbpkvdfwk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtmmpnwmgl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtxxylmtjw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtkuxtzqzu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsatqzvvw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gthflsoipc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtknkgihrl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtxzsgrrbb.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtasjgtgwl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtclrymvee.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gttqvtyrvz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gthcnmrnem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtjoitgnia.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtztdyoqzm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtpznszryq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtuxmqkzqs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtjeqxmsdt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtqxpmliko.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtjpqlnyhm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gthlftawpo.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gturytmfvp.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtocfvhycz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtfhmtrhyg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtropholld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtobrrhher.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtsofkaqzr.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtiwrevhkb.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtjycnpfeu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtisagwixc.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtfvuwsauk.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtdkwxsnrm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtesxovwkv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtutsqyjxl.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtyzpymccv.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtmrlaaccb.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtrhdjhhum.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtdeynciym.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtuadbylox.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtiqfahano.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtbybxesep.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gthlotwujo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtvxbqnrzt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqvjabui.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtrauxxqwd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtoljqcpjs.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtmatuduwl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtqkmmlqyv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtncsoaxci.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtrqbbbniu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtccemaoek.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtmerfjfzl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtxyggyvfo.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgbcaycy.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtdbltdggw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtqjtivuza.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtsrclijvl.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtchsccwrm.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtsalgnqig.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtfpcaskhz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtbgzvxdep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gtuqrzlvty.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtiuiwvauq.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtlhhkqqvx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtcctxmgyp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtukseeyra.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtfaxoimun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gthawfjfkr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtlsdixmvy.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtcxfgochl.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gtdtrxuoet.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtrwvzcnhw.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtvwskcdzp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtkfajhowg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtxgtgcysi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtulfvayuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtzvuwfmbm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtiltnwqel.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtqyytaahn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtftmzzjgm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtrysxizem.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtvrouhbeo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gthaplqlqw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtmnbwrpea.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtomdsoqtp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtypbbuggi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtujymexol.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gthokwcpkc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtikqxdldz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtcstihlfx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtaysjansb.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtttjqwpqf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtorvtuygs.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gtihmvjcfr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtrhnvhklc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtkfvoogwx.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtdayqutxc.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtclrutiof.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtxrhhnhee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtunizqjke.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtccwyirpg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtyfqbdzon.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtjtxgcvja.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtgxfjihjy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtwirexbhu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtfpfdauoz.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gticrhulkk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtaoaglytd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtncbltdth.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtumikyiba.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwkcizob.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtjmjwwcvj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtcjhsxjix.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtrelfeckq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtmfzcwxef.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtyakaqutb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtazrgadmb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtzangjjsk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtuqrxughe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtowteplrd.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtgkvtvwzc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtfjmvfucv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtpfswkpek.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcjpkfsk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtqctpvgfr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtaadnxwbj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtztasaxur.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtmvfrkhbt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiwhmwos.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtbuncjgsf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtslwqjnyr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtkjvwdjgx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtynfamovk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtvjlphqic.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtpsglvlde.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtbzeyajmq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtbtqvukep.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gteeryzcvf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtawhftfux.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtkpkykhfz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gturxmzugu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtumssjfwq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtipykzquc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtgebjobxw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gteuunxcjz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtknxbwxfj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtunwqsgbx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmgyjzhh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gthjixlora.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtvafqotlw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtpuljlyxp.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtdbuoldom.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtlnvrkdty.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtjfesrmtm.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtzyxcoeqy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtreiffrqi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtwbtnyotv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtcxblokcm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtdmiiizwt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtibbolswq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtowaenxvc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtptgrjkek.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtunsoxqug.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtjkrfjkie.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcfgwwtp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgcvuqbfk.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gtkyzbkcds.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzvslyusv.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gtvxtafgxk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpoklxus.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtkkmjtujc.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmvdpnbk.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gthjladkwk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtlolaerzx.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gtmjjxxuya.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtzwnibilg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtohglqckd.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtdnthedpj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtpszqsvcz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gteypmmrxv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtfudjbahm.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtlkkkacby.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gteeuakdop.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtbawdynso.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtlzrbjfns.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gttkcjxduq.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtsydvbayd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gtlxtfwazg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gttqjdydep.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtfampdwmp.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gttpbeuwoe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtpxtdjfbb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gttmxdvnzy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtygefubei.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtizdpdwwc.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gtizxculdj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtymotikqt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtxlarhrxp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtfvtzcapq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtheqrbsim.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtnojnnvmi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtwzfdhrpt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtbgrzofbb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtepkdnkgk.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtxicrgfmr.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtizxarxya.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtacnmukcy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtnrdguksw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtarkaywku.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtlghvfnxk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gthfpxsjop.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtnqvzptla.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtjupzmspv.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtggsiufuo.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtswxqleaq.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtpciqgsqg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtpyrxeobx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtykkgrerq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtytpubtgj.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtrrfpxyab.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmchynglt.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtnkezdokb.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtphnmtrpf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtegpvvbqq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtvrbfkyfm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtejdwttgo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtkrrcxbft.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtfqmtrkji.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtmddaozph.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtvyzrbsnz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtvmbclmhy.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtjzoijpwd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtojwceqdc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gtxkgfyose.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gttygglvbc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtdscftwdq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtefzrsirv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gtprwqzxhd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtztclipye.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gthwjalpmv.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtsdxmnweb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtrqmaulcv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtboylozuq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtlastqlqo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtchzojpql.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gttezwkozh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtpclcpzul.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtnhvibmrx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtibzqwfyk.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtdsgmyllw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqndbqeop.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtiazavgif.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gtwqmhduxl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtvnzrqlbk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtszvweyxk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtoogvnnsc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yonumen.top/Article/details/gtqpkxzfwb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybqaqzwl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxhgnkecy.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtjgnkwfjm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgrkfopvc.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtxxlkdwuf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtnxzxlanq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gttnjssjzt.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtzyvckdcf.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtnfupnkkm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtrrimppan.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtxekybrmf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtjfhkmkag.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gttkzyiknj.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtitgzkbyx.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gtglkvrptt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtwxgpmgag.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthyisqzmp.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtxtkyxbve.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtcjbqjoul.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtoftfmvlu.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gthiewphim.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtdvuqquoj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtshwatwri.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtpiecktjl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtdzxbcfou.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtvswhkkvk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtaidjlagq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpldvsgd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtjskxnway.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtrrromlns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtgggeuyqj.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtmlnnhdzw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtgvmqilkz.html


<!-- 参考信息 -->