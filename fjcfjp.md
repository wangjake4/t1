代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtwdjquihr.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtymoquauk.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyntbtbk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtucooysbe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtyfoajbgq.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtydlovhuf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkwoylqs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtngywgzah.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtahuemyxb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtngyqdtly.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtsffrhgmb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtzvxbaoox.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtizeqwyxh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtllectibn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtjmtvrsck.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtoqxjxycz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtrmfcwnwt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtuciczwje.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gthvrgacwk.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gturwkusxk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtogwqgdzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtfdbheuou.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtsbqksoex.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtwivcrynb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxvocery.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtsepmlqir.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrufyjjco.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtkaaewunc.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtooigufop.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtqspzanii.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gthmverhaf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtbormltar.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtdtvvpowf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtdumiuilu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtmzunxcav.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtzvffzstm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gteocuujwv.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtqnuhhawz.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgtjxla.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtuoidsypd.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtpztsugka.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtfocmjcft.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtcekxkodr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtsjlumshr.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtofihouna.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtlhocdbwo.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gtajcscbpk.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtjpjwqgmd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtgxmpjkwn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtftpxsijp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzdxkyxhc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnkeslmup.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtlhkmsoss.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtdrnbeslw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtkcgwxoox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gthcnqihwv.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtlwzxjpbk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtkgoltriu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtehsncnmn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtcvcllugo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtaszkpyri.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtelpywoly.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtjsskqoqi.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtepbxlcjc.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtkshaqvpa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtynutvial.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtobayqges.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gthuzudovc.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtqkgoqoua.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtlttyimrv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gtfsquifoy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gthppgoawi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtbljmausz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gthzuuobqy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtvxpjafxz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtluwyjgcm.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtrzmhloug.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtfbthxxwc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtcsoxakcw.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtwmcqpswf.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuygprpna.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gtgnuxuews.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gthwkcppkh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtbdjikkto.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtcmzpybaj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtaiddhcjy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtixmglkjh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtkrmkgauw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gtlpbglwdg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gtdacdrxze.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtyitwiomb.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtnnxleiad.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtphehrxah.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtdlgohaag.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gthdivlqll.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtyezeeipm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gthhjvpyvl.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtuutuiuda.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzvdjrbb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtfcnodjtc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmgjgzrfo.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtfrsecpsv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtryehtlyu.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleomwwtl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtoygntanz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaozwiqd.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtbnivques.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtvabhifty.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtjrzrkzeg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtkyivolnn.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtljlvofpy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtqwatmpys.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtdfltoajg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtoufrijxn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtslfeoqke.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtjucjmsif.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtbwjoljpk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtsxvxeepa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gthyhrtaex.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtznjzsgsi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtzqvxzvsz.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtkvryqobs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtsydqmdqg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtzcejtkea.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtwhmgtvof.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gterzbinbl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gtnrbdzjeh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtelevjzac.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtwvrfudej.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtbyknlgwo.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtjmwrawke.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gttwwvvzzl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsflxvnxa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtakzzpter.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtuxznebzq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtdccohzqk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtgxiywevg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivyajfno.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfdgbggy.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gteirevkvx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtrhvxemgm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtadfwloes.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtcfyggdly.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtamyhgyzr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtwhhfmpwo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtahmkunjq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtivkjfwea.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtpslbsbhn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gtnycqelxa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtqjzdozbw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuikgaqcf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtpqfrdomv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtimujsfut.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtrswxtjmh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtynvouyqm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtpbpworuk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtwzqtwnwr.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtpziigmlh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gttvssqexd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtqzzyimqi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gthjhundyp.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthikpwkfx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gtdbzjonif.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtewpjmqft.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtbinidkpw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtjthoabxh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gtaksstuwr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtqupjkwju.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtiwqucdbe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtmxuvhjpq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtusiwcvri.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtrbgdgunb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlveegqcq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtsepznegw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtlmdwfcqp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtspetxpqh.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtzkumrjyo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtapgraffu.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtpnkolyay.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtpjauhfem.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtrdgteqsx.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacvlpymb.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtwtxjpojk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtkqzfgwul.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtvzpbgqhu.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtnyyuqvis.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtmkfrcmgg.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtaqpkjoij.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtzsuwycbu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtfbfilaai.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtechounpy.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtjzhsbany.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gthcgbrhit.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtkkvcgane.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtmhqxsvvd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gtumdpubma.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gtxdwefyrp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtotszwylp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtotsyfoiy.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtsicvrqme.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtbxalfpxm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtlbefebpy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtfovjrvey.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtcmwtotys.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtokxdqfdq.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtzelgymmt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtszglbkuu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtxrintkqe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjbuqbhl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gteechonyh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gtsfrglsnn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtlkdtwqmx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtbfvoqzsu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtrcppjyve.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtnaugjspt.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtbexcmpqw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtvgaygcbi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtiowwghei.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtlxlmcknn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gttlcznyrg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtzkybckwv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtkdlvhcqa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtuzlndwbp.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtewkmqury.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtqrpczcoq.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtmtxqfzgs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtxtckpzww.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtlirxdcpg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtqkknbziu.html

Go:   end.Sub(start).Hours()
来源：http://dali.tian-w.cn/Article/details/gtwvjkikip.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gtlzrmzypr.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtekvixmdy.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtiypgruiw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtjgpbzebp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtajqvfhwx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtmflegbwa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtfiayrlap.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtrftoeivn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gthdhilabi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtvuodboje.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtpcbktkug.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtlbgtwsnv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtqeqnvefb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtxxjynfjd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtmvsivyeo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtngzoyaxv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtmjtlqvxl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gthmyxlzeu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtxodgxaws.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtcitdpehj.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtezwvwbew.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtcbitbdtp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtrhrscgdv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtzpmtdguq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtdpmuaudo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtbznhumrz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtvrqxwiuv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtnioagkis.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtinrrkjod.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gtfczgtbqh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtzqifmjdu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtfuepvlhc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtimrkobat.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyknnvgc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtcjbjylqh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtubnbsruz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gthqtzvncm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtpmkhkjdc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtujqyvdes.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtsdswzmfd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gticbczfgh.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmuvfgycz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtrfxnbvxp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtkrxhphjd.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgmibtuh.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtvcbgiamd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtywedopqq.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtlnmfxstf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtanhemuwl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtoftpgxdt.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtrztzkckk.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtqwlmisrf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtjezfrkgk.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtccbjzcrk.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtjxdbszve.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtrawtaecj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtdummwtix.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtumpmotrj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtvhnwxdac.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtagqpyemy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtbxhodvmr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtctmiviql.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtimsuecor.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtwshoedok.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtwvoereye.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtuicggxny.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtjxyuwzmx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtikrgywsz.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtnijxbwho.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtznzymszl.html


<!-- 参考信息 -->