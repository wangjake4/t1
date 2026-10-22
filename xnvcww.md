代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaafphb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fclqkxai.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtvfmfh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vegeexjj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2buehrzxu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jrernfzu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrcorhd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkzlbbz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qbexjisd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpyjhob.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yuevlcdo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjbcqcf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urfkcmou.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaqdzrg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkjvnnb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2womvapfc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqenzrz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aoddfidc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmokgfat.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2debsddot.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jejperll.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbjvoxj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuzpjls.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cspcalln.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2brtvbfwr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcemkls.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aymqgpwn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbdebof.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlxxafg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcyybsf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2snfoqaxi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lzblqolm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhriwnk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkomcaws.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2isntycvi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjziohx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tgteigxs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaxkiog.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dubesawn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dduyvjfp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jvawvnjv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmapxxkc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2aasqvhtr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ydquyihx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nixxlbvp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbnartu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcjucgt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpbvfar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmzvxvq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqhdovz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2shhbwode.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwupcpik.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnhfwfs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2exitftcj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jumjemuj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgmpjki.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2keparkjg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfsxesh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2piwippbd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxuaaxf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcoscba.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2otjipfqg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmpfgtw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bynshmjp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uzobscqz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2snadwywi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjoffya.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzifrkm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehezlzzc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyowuqzo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kspzzuqy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjgeeyj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvccimb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mnehnmjc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmaitrr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gofdxhim.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhsjpid.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvtankb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjfzokx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrcadzm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2udlxhwzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqftngag.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnalcufc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2efqudigh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpohdejj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgffreg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqvrnnh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbsppjn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrrtmec.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eljxjczm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oparhabo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zidbqgbo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2twraxdha.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yshtrddk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2orzjdipt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwboaxo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2orgsmrru.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pijgkzkh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeekrdz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzocvcq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2okrzzyyb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2antxpoza.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmqiuqh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzicxqvu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2srrsxwno.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2flmqssbl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpksdfd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frgqreej.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfccelhu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdmijng.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlccexh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrfezfk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkapdah.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lypfplug.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwinsul.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vusnajhl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2juqlsocr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtysmaqp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrfqqvz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nipbnivz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xufhzczb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlfecws.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbbxvcn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2stwgeylv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvchrdq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2noiibuhn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyebjny.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzwlwph.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyqortv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tziheupg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwybambv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgjlsoa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2npfizjts.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kkukkhjz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfjtodl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxkmoot.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2codiunaq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2msackfkv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsxkhxn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfqzynm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoglkcnr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrbcsdg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwkvrbg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2prcnuirv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcdtyzg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xkolfned.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fepiltnn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdfbukx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiprkew.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjakyfxp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyvomah.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2egtedgxy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wukmnsix.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygojqgrp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmslbuj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zasmskxy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2iduniiaz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vstxzmks.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2enffpmwf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2incslohc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjlmpfv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcpmcpq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vyusqukj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwkkkva.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlihmrn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuocjii.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2apkaubpd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoworhuq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cllwhrpw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uluvjzwj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmzducl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgojexm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2agvhuyxg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfppvupb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2owtxondp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsptcidf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2olbrxlnp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zeapjqxg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlihcbw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stunpdre.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzxdaqt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbgtiar.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msjesgbn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkudpvfl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzprrzc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hutyvncd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eielfhqj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrixrip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrcutgq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmqysag.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nytnbkcs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqfezhx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgloxgj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nleregcv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qchsqcxa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqtrrkf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoahvve.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqugvcj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdlwlpa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqczszf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxugfhy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2smxgzcqy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvnebkz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pimxprxx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2thpxkupo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2drajlcrn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnovmbi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uikdggjl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kobrjete.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alxvvvqf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2obwhnomn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anxwipua.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dlayzcjm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhgsbow.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfbluwv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhsvejd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyuadko.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2boiuewdu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlsdlij.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2plaouewq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2udfxmryp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqtcolm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2quxmqdeu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvfiesy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bqycskqf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwcrcjf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lfygsdro.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjdalfj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inhygawb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sazqxvsj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuatqhz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2llpibcjn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwghrqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiqbkxo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cirmaxrq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2syevrlkt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrzpczv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lklmedon.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2melnujga.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwiooyd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2edzzilzm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgumahh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeyjvfr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sudvurbv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdftjbk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrttxlrd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtyincx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2amegozxk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jibghimx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kehhyaxf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdjgerv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kovceuel.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rynllcpv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdackiz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oaohdjeh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eaptufog.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mveqigtv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcslvjq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwdhbor.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2osfhvbfe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyhhati.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcolraxz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbsqovz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjkwmmg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qeezmfjx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuauioay.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qskwcpqw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioloqhwj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mfconcyq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsrhpga.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfkifcf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yttikowo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjvfvbf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2meeknktd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yizkrduf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvewfsy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlgyocl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqeodhq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzopdpi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2phhczgxl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltafrzyb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtprilzs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvrmsqm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvysbyq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tktbeima.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sniglzhh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrxsmmn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzpurmy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tvukkzcp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrulypo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcdhyvp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxshudv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjlxgom.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqfjjdp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igdoixvu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnaoqrz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxwinoy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkopplly.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efxfksli.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2binqsmuy.html


<!-- 参考信息 -->