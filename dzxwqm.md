代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeobnyl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hielsksz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspvjgmt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfscioou.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2phpjerkh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utofksnk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2brbkgsmo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwdmmsk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pigkfavx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaukngv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qyddeofh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yareyewq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbxpoia.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbmggfj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoxjmtm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsulnwel.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkasdwx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwhytvg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcisuvs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsaxwlg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vezmwlio.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwdemnp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbjtjtu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoopzan.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eujbbkcm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjupippw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzrwaqy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iyveuffq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bunijyrt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlsoffb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ncesitnw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuzeahb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrplestk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jghbodih.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtkrohl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2npkyaffl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njrkticl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2txhlvgpx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2plganyqb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjevxqzv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcavjznn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gldkutgn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqastxz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vshbwsco.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2viehikxx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2botgckcw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rngughna.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoawihr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyactshh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hubfsaot.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeuqumf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzfqmob.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yedkewom.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2thrbbfwh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bosatwqy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmjcgko.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdlnvrn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wioxfbcd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvmuvaj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpweyxv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqdyqqb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dsivonhw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgptdse.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gluvehng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2euwvlcwf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvggyuxj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ynibyvwa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edkpaorh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrouhov.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uirrrqud.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cciaomtl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxkivtu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nclpznmb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjqbgqz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdpevic.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fflxpull.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnsfarq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sreuoqci.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxxipac.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oarqbwov.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlhpqsp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mdclwand.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfijejb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbqgmvx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xonfxqpe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ypurmtnz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vovyqrje.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2npymtnpg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzlyykr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2opmjigfd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbplpbia.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2weuxukto.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxjvqkw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxmrftr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsbyvvz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2skvzhvae.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoekupc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzhhgrt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfoetmz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iqidqjdd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfefjdc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhoyoos.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ersthptj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hygnefwl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsmjzif.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mflayuvw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvidwhq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkrdoqf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vooryjwd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbbkxka.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcvxgpa.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfgdzrh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2grgmrjvb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qetpmkep.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vyypvczo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wljtfpdj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmarzzp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaoftdf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ddairmjl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhqzyvi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqakkzf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2chnzaboj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrsavie.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wztwqrrb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtatoga.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wsomohxu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzdffuj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaxlijq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnjeekm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pznexaul.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qukbtzrs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfqytgu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2raoiecmz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmqbwme.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cbownaik.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgyzpak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjicwqh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2riiathar.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcbpsoj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odfdvsoc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsbxawm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2garbqraf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcbyqcz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnifdklt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2unvpoyoy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iejnrudm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqdwzbz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2isajofft.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mhioegbk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lqggwchs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaaoovf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbwpyip.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brstesik.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyfnsdh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2otebwkxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpecuyxt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpwztav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwmgirq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrgvzy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ongtxowl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzocixzv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yybavoip.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zafttoew.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdlztw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqvxdyz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wumlsngp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfyqtto.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxhhxwo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwegxrrz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqikuae.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgrusko.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rumxolty.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2klmmklbo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmcbgud.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybywrlwp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfanlrv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgpohnz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfzuryd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmucsrsc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocovomex.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2irwgtvlf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcyqdyn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvcfakr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edkvfrvp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvvstpp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drqzfcgb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmobvnux.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2atjdnrxp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gaveypwn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtlujrb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxcnrgu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgpatnv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lytefwyd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgwzrpo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnichfjn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfnrdjv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmneqmff.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uawrlsqc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrodhal.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2smakufla.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnynphuo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dimrcbdk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhsmqtf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hpceaibb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjzrtol.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2genohgqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbcqghf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkfwjhl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2whscqihs.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2isdklimg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfgyovn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbmies.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbqjsyj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vygnqosm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zveppafi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbrskoq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tplfdqks.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwcauxa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mckbitgu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkqpfuv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ceurwmuz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lctysjoq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeyqgdz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwjpedp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqwsnpp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znzypkoq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntueovjs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2scwimogj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzfuzti.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pywhagjv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lupovwwe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teajqglm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rogeimuu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaoxqzg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwamrmr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzffgkv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eccmwkpj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2embcbjre.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ksghlzxv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbvobwa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bttehlwi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgdrimn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsglsmo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvevsqe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npzrbttt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmtjzpt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsklxoy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2oryrqvbv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvvewxw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvoguen.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaynddx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phwthoyb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mkheawlw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2osmlydoo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2addgdekg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seoweoan.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zixatwhc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icclcfhj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcovywyx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwwbxeb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpueizh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxllkrxe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfzenck.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qywxxzqv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvewhwsy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfezmmpp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2heflkxwc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzdxgov.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txljktkh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2osezyvmh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kggbtuqi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2brdcptzm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oszpkymt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqqmwcp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvwptvz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pazwirnz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taamhibb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrycyjuz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuezqely.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2klcupbmu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkcnsii.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgsuwmy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuiwkbm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyxexpt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpkmvds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxxjxye.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2znlncvhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avtokwbr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlfbzyj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfjzhiu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrayqwxt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgygdcu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wgygpnnv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2udrwmwgu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlwukdm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbglkvl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqohxdl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjecilkr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xkziyjyu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmjhpzs.html


<!-- 参考信息 -->