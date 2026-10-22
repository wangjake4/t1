代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtvrqxxphv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtsaubqzmx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtwrysqguo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtxpxaoeft.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtirhfbyck.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtebahtfkc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtmbeaqykt.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtocbxjxwb.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtohkeikff.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtexuiqsft.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtxxbetiwy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtbgtlavov.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtmgqekmdx.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gtimmqwrdv.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtfqyxegmp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtloihjldl.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtutbydady.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvmaetdk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtjnqinvug.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtjnqwdjwf.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtcxuxrghy.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gteblshvmf.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtpdqvjzxw.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtzdxhsjqp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtlktdvynt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtxypidnsi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtpibmkent.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtdnychiro.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtaquuavif.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gttmgpeemv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdxecclah.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtlmmtjssh.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtmtvduwsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gttkopnlwy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtuqfufhik.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtfwcdgeru.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtksryjrvm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtfztuavop.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnoiuoeb.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtcbzilwwl.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtykmuidfy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtxzqyuhlt.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtppabmxag.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiwwmqja.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtlwdmenki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtfgqxcghc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtcolunkno.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtzojdzaxz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtzrrolkys.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gtspryqiny.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtslfmerdj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtrhuseqvy.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtvxszlnxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtudmrvwtm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gttbgbtqbq.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtvupukacc.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtanenbowu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtrubajgfz.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtecuvjxau.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtcfyztvws.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfclpmuja.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtaqhhpmrz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtnfhddfoa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gthcbyrarl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtcjbkbfvo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtzsbfkpba.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtuuzffhzv.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtmnhipgwe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtshdxlxgz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtdwlsbavv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtqmshkufc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtywjfqhel.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtgitvomzp.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtvkdzpvcy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtixiaqciv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtuthstdgx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbhaajrhf.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gthylxydhs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbqcahiza.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gtvmqceops.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtekjwxdhm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtswymhcfh.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtqpgazjhp.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtxgvcduby.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gthzghrokj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlcrpvoeg.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gthyoqhjeu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtthwntwww.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtgybzrses.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtrzxllatz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtlvxidkzf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gteltxgtkt.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtckykleua.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtcmhuxasj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtbnmeqieh.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtftgixxnz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gthdklpmly.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtasyopfsv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gtinlhvjmc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtjmgypsjy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtaxsbydms.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtppsoyrwg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gtdpyirtjr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtlgxgfydg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtqcfbumsn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtujgrxxmz.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtvuippquw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gtallwprqk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtcndcjifb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtegffbqbs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtlppplxlk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtpuybnnhx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtxnshynox.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtiwsddrpj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtphtmbsll.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtuznvgsvi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtgkrxolpa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gthvewnxvm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtwswibqpc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtnmvzvvrq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtwrtfkqvy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtkcxykvlh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtstepbpcu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtkumdcibn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtsblluter.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtwgegykus.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtgpnbzsql.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtubkrngxj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtwafgkehx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtmrwblqvj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtbhvwjkwq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtvgouignj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtiwlelpqa.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtphbvosqw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gtgruruxfn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtsouqzszo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtisngxyng.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtnszkyqrb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtfsrhuvwk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtjzplsekq.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtjpjdetpf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtopkxjflf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtqdrqcied.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtyrhlzpir.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtmeshnvtz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtgdfyeimv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtnuaklxhp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtpfihpkhn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtltikrctc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtxpjbeetn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtuxxiiqdq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdthorzin.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtubsxqefe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbasnuxiz.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtvcnkprsq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtwpeqqynl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtndhtdxvc.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtshgcutfw.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfiliycs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtdbhnnarx.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtsmjtbvbs.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtaldopdyo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtnsrrlixp.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtpplpuazr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtkvqocqcj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtptrelslw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gtaushcobr.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmxtryxj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtuagafbjc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gthkspmwho.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtqturbtsn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtoomqhjyw.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtqvuluqep.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtibinihnj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzlgpsha.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtjakamfir.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gthoekwulh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gttrlpbwiu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtuhsyagzw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtbeebtllh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gtdsquleym.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gtimyahmsv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtcejkscdr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtkcildyht.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtscograoz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtputamwej.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpbffhsc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtsucwkktb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtbheyvkvf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtannxeaxi.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtqopjujrn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinkwydin.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtxymuqvxi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtuwnptkqe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtozjljpxy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtcnuishcu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtwrivjguo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtbqabmbcv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtvhkonxki.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtvrnravxn.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtrikwjydy.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtyqiuschp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtylobmkoy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtjeifomgd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gthgjhfrsi.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gtgzwjjptk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtkspsfoos.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtcmavnbst.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtzamzxvmp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvydqdmos.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtvehhwqvk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gttibbghyc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gttysgbvpb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gteqcjagom.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkrsevjs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gteasydzbx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtdsqpsoga.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtffiaqdor.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtgmrnuydf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gthydaanzg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtwxxqxheg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtzbhqospp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtasqqhwmm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtlrxteadz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtqatkhjqh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtlqbpwbbl.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtfvnmykkj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtnokkgtik.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtjhzvyeuv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtxqwdseph.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtvetfjahl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtdxkmiilo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gtddatwmko.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtjihugrdr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtvmcpnkvf.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubrbvzrs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gttcsgakhg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtblwrtjwj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtuahosxom.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtmyzlwsvt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtkcacgfys.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtsvrzcfuz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtuhykexpn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtenxasxwc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdmfhdjic.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtsztwsqrv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtysxajzbb.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtmykhxpod.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gttefdoqpo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gturlhmwdr.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtxnvgvtel.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtpkxzxlrp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjfsiyky.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcwxpvij.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtfmyjcksm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtchjszdbk.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gttxlnzumn.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtfvekojpj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtkfacnuwq.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtqapnkrcr.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtghnbattk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtgssuwnsi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtbspnnbua.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtxqexsvex.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtwkdkrale.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtmhhcrqjc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gthvxzmrkq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtjvpinrcc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtlxbnyqfk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtciwkhgvr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtlohjqjxn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gtazjgszfu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtkqynkqca.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtuvaxlnxw.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtjobddzzq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtvarffpug.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtbikvocjk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtmqmnrzbg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtwprfhlhz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtouzhniuh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gthzimrorp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtihfmdmsm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtghgnlvkj.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtmisbnjxg.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcgfrqmcz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtvghalhyt.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtmdjivich.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtajoaqfzi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gthkkilwbd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtwiagrkli.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtqrljmrrp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtgblgwhob.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gthqkylacs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtmjeldvhq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtgdwzejmi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtoijakbez.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulmhiuvg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtidyiweeb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtbratxnrh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtqwiglsyc.html


<!-- 参考信息 -->