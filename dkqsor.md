代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2vxtqvnts.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gt2pbwedmqx.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gt2glevqbvk.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2bnopclpq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2azkvrccc.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gt2thcefwhw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gt2yhodzkle.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gt2yrjkazzl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gt2srbqmleb.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdnkvfvc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gt2stcgxola.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhsjmohe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpunkbqw.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gt2ejcwjyjw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gt2uqwsmhyt.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gt2owzsbqql.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gt2sfdogrds.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gt2xbiltawq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzuxnukz.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gt2jjjefvfq.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ixnblfti.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gt2bbvqmfpg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gt2ztlmjslh.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahvnkqqf.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2qmgwvwhs.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gt2aybpofli.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouznogpp.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2vvotvjdh.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2sobphdza.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gt2lzcuqapo.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gt2tcuubybw.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2geasssqy.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gt2ecvamlsl.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gt2xffclqjx.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gt2uqtbedtu.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gt2dfnqivzj.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gt2ygtuggyl.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxjcyjgb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfuznftx.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2cmcqsrso.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2pysovata.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gt2lwofdfzx.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2qchiiykb.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gt2wpclmwhi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gt2dlfmxdyk.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gt2lusfiugi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ecpfdduc.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pheszmwm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gt2jpdfbjno.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpczjaag.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2sdmttqhs.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gt2weclrgim.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gt2quqbqjzz.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2okrbmgan.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gt2lgwcqkqj.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gt2bgedotwg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gt2psaupobo.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2mnnkywno.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gt2boppxojd.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gt2kehqywnk.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gt2ctymjbay.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gt2korkbnca.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eabzxwuk.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2mkfhsmsm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gt2ramqoekl.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2lpstbuwv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gt2mtdxbpnj.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gt2liusdioy.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2oaxktwio.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gt2bdxerzur.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2mgevodhd.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gt2sazsywiy.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gt2tdwppmeh.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gt2ywdyyszo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gt2fnpwrsze.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gt2qrhovgcy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gt2fqajrqcy.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2udeiupkv.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gt2rymqhrtu.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2khsqrfra.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gt2fdudayet.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gt2rxdxdpzw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2hsyofrjc.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gt2mwogtxlz.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gt2iavosgif.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gt2ueucfhez.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifkgnvsd.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2liqdrrlh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gt2bifmeftb.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilhsdtpx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2nqojfyzy.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gt2vaewjado.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gt2dcuhxzxj.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gt2hfzknzmp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gt2rkoevivb.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gt2dmwfadng.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gt2hmesmrvp.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gt2atuhrakd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2ncugejcy.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gt2qvypnujf.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdrhsrxh.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2yjdnrwhj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gt2mcowssgd.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gt2qzqlxlsc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrnsaskc.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gt2vssuahzi.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gt2hvodbxac.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2igdbtjjv.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gt2dvqtgepu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2arnybxet.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2ombjnyfq.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gt2oscnacyh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.birdmap.top/Article/details/gt2ljnxokvn.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2kmtbzlcg.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gt2mkeggecf.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gt2bxcdhhgt.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gt2jfezgxbq.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2lhkidavi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2muiyywhx.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2kkeltqyh.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fylynmcv.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2uyxyokkr.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gt2hoarfjnx.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gt2uqnvkqvl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axzlwkrx.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gt2qpqtoxsj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gt2xnqghrzu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2eoifanrw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2qoyvvevh.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2jnbrgoeg.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2voakjrmh.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2xbmhpbgm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2nvdezkug.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2krfsvxjv.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gt2buzaseuf.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ypfkplsm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2nfsbwsdm.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2henawmlx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyhgzsvv.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gt2kzgcjmtz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2mfpnnhxf.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gt2sbalmgvm.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gt2ctvzfjml.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2thpneyyd.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2btscvubr.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2ruhipeld.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gt2qatjppio.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2kwotdasm.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gt2iltbqzfw.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gt2syyogmhw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2xpzhqcfu.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gt2cnliprji.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2ydiafocq.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2zppupwqa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gt2kvkmlyac.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2fgqavlux.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2mtomawcf.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahznvytl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gt2xclwpzbk.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gt2mqymbfff.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oooonule.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2tufikwmb.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gt2omqqasdi.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gt2nvkmozux.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gt2mgizbdih.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgfisdue.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2zgymfaup.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxdzuxza.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gt2jddsnjct.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2zkdlccsi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gt2zwpqlutq.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gt2floeduvl.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gt2panxgsjt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgrtscz.html

#endif
来源：http://dali.sweek.top/Article/details/gt2moqueidb.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2yuprtdif.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gt2zilcliow.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mghenrqg.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmagfocb.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gt2rezqzkyx.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2kfsjtzal.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gt2hkykfcbw.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gt2osooiixg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfmepysv.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2irxbztsj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2bvalsimg.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gt2eeqctxvf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2npfbwhts.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gt2spawdorf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqjhqwxw.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2mbscopli.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2dcmoubeo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgtijtr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gt2ucnkffhf.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gt2wamerqur.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gt2ilnbxseg.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2jhyzhupk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2yxjdqqfb.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gt2caonbied.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gt2zimxmucf.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gt2yxnyyovl.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gt2enkxcdcx.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gt2chdcgshc.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gt2mzcwqzrs.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gt2sctudyzx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gt2agfrefey.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2tntxopyr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twdoswjo.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozkfqgjb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2klkkgpyo.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2mttsxfff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2kxvazgel.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gt2yedbsjmc.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2tevalqgc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gt2bxpjkucg.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2kruuilub.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2nnlzziob.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2hlqvdaza.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtneuofm.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2aldxfsxa.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhvdfjmi.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gt2xlhxkqnt.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gt2allmziya.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzqpptvq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gt2adutovpy.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2skxholhq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2limgmryh.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyynqyqs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gt2gfjonfug.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2mupiigwp.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2oeeawtsn.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gt2thimiqzx.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2rcotaghq.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gt2pllkhxiq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gt2nmnelgze.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gt2tizzcleq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2eujuaivc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2nglrbonk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2zfrotcdl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2srqmvrjr.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gt2lvvqesjh.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2uiokntsl.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2chjyngwv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gt2bqfglika.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gt2kzfsjjec.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2atdrkedd.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2dhwpuzqj.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2qweoxorb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ptfzcujv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmlkqxgy.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2mgfyqjiz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ywyxptjb.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2axmquknp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjyhcroa.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gt2iycoescv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2ivbbdqsi.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gt2aihnvwfs.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gt2sfskfung.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gt2gulazoho.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gt2rmjyjrfq.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gt2ukwhccmc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2qfdlejwn.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gt2vkerrxaq.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2dfctumct.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnivzxie.html

val m = mapOf("a" to 1)
来源：http://dali.haohaochexian.top/Article/details/gt2nkrdazbe.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gt2fkjsozry.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gt2djttnklv.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gt2jgqgvqmo.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2zfstpjuq.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2zpdqtomq.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2sgzpvvjq.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2cwfbjyxb.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gt2rinjvlen.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2drnludft.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gt2zbkljzlv.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2xccgrrkm.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gt2bumcpcai.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gt2hyeinnop.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2utmphxmc.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2qovuzdsz.html

for x in a { print(x) }
来源：http://dali.yuanzhike.top/Article/details/gt2hgpxhzks.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gt2ounlyzye.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gt2dcfxqtga.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gt2icizgtji.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2bvvoshrz.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gt2motzmdgu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2trdkgvfo.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2hknnvylz.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2upjfkubo.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2zmazthms.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gt2gsenvxpq.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gt2qywabrxr.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vouewcjl.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2nndmcevo.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gt2izhplivu.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2iogoyphf.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gt2dhammmst.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhaogdkn.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2clpbmllm.html


<!-- 参考信息 -->