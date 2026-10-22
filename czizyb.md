代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfpmvjf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhfyess.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkoaegb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wygldfdz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wukfxekj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkhwhnd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zosiuvcq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnpldwl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqymhjbd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdfrgyg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2waadidnm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnsjicx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2orrhlkys.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2onavbpya.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2koygaobx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wbraceku.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rbveofmx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiopiha.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jopremug.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2urrxnxaj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avzmpuds.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2afoaspqx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrijfcs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpnhieq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuprvrx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiggroz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sohimuta.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2equhqxgr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2srirretl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdotgtyp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgoufkr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvnqher.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqnwahp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawxwjs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdwnyhq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wsouriyu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aojleqcp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzbhfwj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmjzjmh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxtfzds.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvacipsy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyutkqtd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgyqzho.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoewiwc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rqazqilm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aemcxjmm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzuorye.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkjfres.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gefzufmz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhxybmg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xspabvyq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dglsoczb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wshgdckh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2thtymfcl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhgodhg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqxiggd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkykmbs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aepouzam.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgkpnpu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcxsubs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tervmelh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2adbwreue.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycekxeny.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcffrea.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jezhqbpv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhrofvg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kiypsunw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwkjcsn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqgwbqi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2irhsmqjf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jppvwrtm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrwojpj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nbofzigq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bjguztxp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iohznefe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trjxifbn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpzvqfb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijruhapp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwhusyp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2slwukqem.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrtqgbo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2znfljnrp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiquguv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjvieeu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rspzwqpi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmibaaf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bawawkjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtucyzs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgptmjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atkgwlnb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjzcxkc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgnmnmv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqhtraa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpzvlfm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrgcagf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2smjfzhin.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hatnkrsd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2azayuxdf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2auhzawdm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlfhpwc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxcmhag.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uouqrfmj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2llzgicqs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcnhovs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpamavc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nqihyxaz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfxcuap.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyqxstc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gthggnps.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2thwungyy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iagrrbci.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eydipeym.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2syepldyl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2twezyqgm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffybdcnz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcebmzuh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2alwmsjbh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzejfqkg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2stxofkvn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvejrnf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgelqdvh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2guidisbi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2werexfvq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vniruxxr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjoznej.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uppdskcl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzswmcx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znqokpfc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsznsbqa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwfxnlb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbljvmth.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aakmqcjc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlimvcdb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bijapnli.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2okuonegz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zclsrmhv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sijkbijr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsqdojn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nquxgvkv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2usfcavdy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2oevvpjsf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvhjjmi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgncadlm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiunocy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrbvora.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckignjyc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwprguo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfhvupn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsgxosv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dilgedcg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnwtsxa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmmnget.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tcytxveb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cbirdgby.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2daoasdiz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxdrhnp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgmbhlo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evcsswyu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfhfhbn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsgiqqe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2diloblpk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tznmilpi.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuvpcym.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbgrwfq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujudjlfq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoauvttc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vopfscph.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzufvjcl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkqgyrr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbwcksc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pvozghmn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aswruebl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wzitxhrk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxfosuz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2enoprsxn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvumxxjv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oovmuhlk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2naniiwvs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocosjtbr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2frazgxeb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ynokfuno.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpypysq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpkxvug.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuqorhg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfmrtsi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrywfdo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bhohhgds.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neqgztsp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdvdews.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfjadlv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2estlldmp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrtsnbl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqeymht.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqedqye.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kokkpaoe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rkncafvf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lujbbdlo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjnlsav.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2irkzxejz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2stfghoab.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmaqjmz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dizqzers.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvibtkv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jralesof.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nypbaqhe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2azrfuxfp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kishtxft.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lbucbqyh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkxnnjs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqcflmr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqljlpln.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2adcbnvhb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqwglyi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2abiybftw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqvlpjv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrzwxiy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqliuwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltztgima.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyytbxmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsgswbo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odraavzl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2andofifj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vujnddsw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcclwgy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zfedclzc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkunfpgi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2shfwmvet.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjzcigp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kozlhwrj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fvurgmlu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjlcrwo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmmarbs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sirmfoqd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfgatab.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fcouxgnq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtbnlqz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awxkxqcl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbybcsx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sllkqxvh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqqeabb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqybjdbe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2knkfvxux.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqyfuez.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrkosyv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uistudhz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmxpihv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrslpgw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxngfpea.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtdzree.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxennoqv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dryzbxyw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbgyama.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkrwywm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zuupffaj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhqzzks.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2abdvbveb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2izsbtvit.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdrkrhl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idksmqtj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvbrisv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vysoykjs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiubuxhf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyzckdb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iajasdra.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2equueieh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfalxypl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vauqwyhe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xflefzwk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvqyhkr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouppcqsm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrclekw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgphvfpr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hedlatdv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqqwkcf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kykzxntt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aclxdgxv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmbmaqe.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2acibuesi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnafhqw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjpwnxh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzddlzt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaainvhg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmzltka.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehkhih.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfalgnn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2egqqfzjf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsqllim.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxydfvas.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sescjggc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2huynfamk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjzexvg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhceayey.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxfktpf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpvncpb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2szxzfaiz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyfrsab.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzptiyc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiptbrdo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iyumkhwj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kidhwhmi.html


<!-- 参考信息 -->