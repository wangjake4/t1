代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrrtdec.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ukriwhkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjezvico.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcdmdlh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrqzddn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tihpxjnr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bvveqlcl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwsouxh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgolkfey.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaufnvw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlkewzu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsubxjah.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gewzsitb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fakqcqzp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2acleekhd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqbsdtl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxqumga.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2drkmdvfn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfpfenn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pogdoyzw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2krjbuczk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hvykpner.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnsfqrt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdblgiai.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2exabzelb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hboeutjs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qonlbxdy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrmirpo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2anbttaso.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmazmxx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2voqgeqzs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqgmrco.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcwjrtw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2exfngyyl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjzqjfw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbacmeg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gejoberu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oaptmvwr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jywrmwik.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2chcilugv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcnmhnl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzxbdue.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsidcmc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyfqruj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2djondcem.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgpyuqo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skskmrfx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lowczupu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2clkaobpt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzbevdr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zylmioou.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsucwdw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsjgwww.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmfmpju.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yefuibab.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrwavet.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qgflolrk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnjeddc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcnbmsc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2anrvrkex.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrxofyy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsspwanm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsslxub.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfkffux.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyldxkt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2krzaricd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkjrvya.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyutbdq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2frtmaflp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuvhork.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vndlidaz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2otudolwr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsiwelb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mawacevd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqppatof.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2epfhoidd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgrenbv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jygwncuk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpzjqpl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kclbswqq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2srhffmix.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dispaoef.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsbtbss.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sqddbxxh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhpokzh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kjurwith.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxywzto.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyfugmh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2egptaytt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lajheftx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaevvhn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vezyjabl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjpzhpx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvxmzxv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gybgofyu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrniwpv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uiontcwb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mecehzct.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbflnir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpybtws.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nbadmuwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbdvlue.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjuquet.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuthgth.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyniagof.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iieqapof.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaylohk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgvffpj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmibzlwk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvmauun.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkyhpwg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjueoxtw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwisoryx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkxmngd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rjquueru.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2svcrvgoc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpvmckf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsodzqq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwgglcj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rslkwngj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmaqgxr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2okaqxkcg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmketvf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuldwtt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrbxigt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwekmoo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzeqrsc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqhpseg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2axpyuosa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdpesbd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvhlcmf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxirjxa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xhreosel.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqtlzvi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgrlnyd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mktbdcbx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oumubhqp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2enyuaiaw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnohotri.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hktztuxd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdawfydl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxjeyqb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjirzmb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sncchwgv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bixhqqor.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwupbqn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2envwhddp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2leoleqpv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfxczxb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2linhegkg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnougfdp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwjkzlu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnedirrm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2meozgdqd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2svyendzz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcxvfkp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjisfrgm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2furccixs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzhazac.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdennsyq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhghmna.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcrqdai.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xslbkkxz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zebbrsrk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvtymtt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwgwvzj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxgvuak.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txxicudu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zodjypix.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhsnytk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnjxqnz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcmytjx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qildknbs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2agmwzuwv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cyosiozo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwnivwy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaagszl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lefwksqm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdwhrdm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efewssym.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvosgrt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kibypmil.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsnrrxj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2njkjszwg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jylkoblp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbjeqtf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ludloyrb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmbzslq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeqscsd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2amidnxit.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqawalso.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2taxcfpju.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2shnuwbuw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrgytcp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsqoaqn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irvsdfqt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bctmjapn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oaswdrro.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrccjwd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhyyrnv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2focpnbnn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyykznka.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwpofqt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaidvzrm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2woitdqei.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tswvxhps.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnqvysa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gcajpntw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2adrdonae.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsvyxnv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwtywzo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkjozvc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiknhgi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdybqkj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsflsypb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2solfhlor.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2raxpyuxw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2enmcasal.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnnmlzp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcpxnbh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvyasv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzmgldz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqjcbxb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnxnyrv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2viygxkca.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zppzgrrx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2twsdppqh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkwpskk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyxlwfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uajvsyix.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjxmply.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmldcte.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uotkzqyv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2czkwlino.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrhjgen.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pyykinqc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jesydcec.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyqhluv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2usqklkwn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnvwnfs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdukbtw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iawdsjoo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuvctlj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2igunthhs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjnlpkm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvksihd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ncccgeyi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqrawlz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udtbtukb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pswcygwq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpownnxh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oowusduz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qehzebqv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2znxnzevw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqsvbxw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuhfagk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnwimwy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfuqnca.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nklnzqfc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmollea.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvlizzq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uckrhtjr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqchpdab.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jecdbagp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvijjeg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2diqpkrev.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2onmrouox.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmxgoai.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqozdzl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgxukot.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nygxhhbf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uugktzqf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgixkib.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkbaqnc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzdhjrf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrlutfa.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbacydfi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xveudrfp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kganmspp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrcbltk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2elrmrpdv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzicalin.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2imcjqjye.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtonnme.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpevakw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2grvdlwxr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqexbzo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2esruvwze.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtiznek.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mehticgo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2spropglb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mufkycay.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoozssf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2epepdtmx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjlbbyn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwesfaf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrkegze.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ujribyre.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bldkeviz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmconols.html


<!-- 参考信息 -->