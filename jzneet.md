代发 wailian999

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtkwjvywzl.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gtnnsbmtrw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtpfvmttcr.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtvkizkccp.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtuxdnoiqp.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtuqktypdi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtnwncihez.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkmgbmjaz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtbmryvfam.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtsfdoxmld.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtzogvijbj.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtlzhpwcwi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gteqczckrn.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtquafcjnj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtghxdpvii.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gtifklwpqx.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtsbtkdwoj.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtigzbmupo.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtzhzpetzv.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gteuovmyoz.html

esac
来源：http://dali.bjfxy.top/Article/details/gtljxxmqaz.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gttfwamhau.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtphzwgjrw.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtcwhlguho.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gthfyrmbvm.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gthkgtzysv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtdlhebxaf.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtcwvtrbdd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gtvdgzbyjs.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtnvlcrafq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtngkwqokz.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gtzsocjlxw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtiwipbljf.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gtfgmyepjp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtbgmensfv.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtvpagqghm.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtskiwrnnn.html

[R20] 关联数组（字典）
来源：http://dali.pengpengdd.cyou/Article/details/gtddqwvfnf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtqgpuvzsd.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtdnoruzwp.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gthyhpskaq.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtjfrjecvm.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gtnonjsauq.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gttdnafwjg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtecvzpjbz.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtehaxrcif.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtlmvueqpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtcsebffib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtwzmlfqlp.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtbhgdednj.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtuuncldjg.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtqvzwclwg.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtguienuti.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtyieqoaht.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtvwdbhuiw.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtjbbeqqus.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gthjutmmah.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gthaljttwv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmttpxvnr.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtxdezxlwh.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtctzrytif.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gtkuawtyps.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gteqdqyvoz.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtqeowiiyn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtipktzoqi.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtoejkiqwv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtnutimqvy.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gtaqoxgltb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtacyermlk.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtbalmlziv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtmixuiuhg.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtwkbfbsrg.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtdccewsjo.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtxmmdmfof.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtxgxfbtek.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gteiutcpbm.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtyglblyqu.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtpyabrrem.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtvtebqtzl.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtzdbdsfba.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtaxdslqgo.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtdtofopqh.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtlyukgsgj.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gthzvekvbv.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtedqochbs.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohwelodg.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtbfxkhgeh.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtsjtemjef.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtzrnheuql.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtlgrssmmy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gtchwpxckm.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gttvnpevdy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtrdvopkkd.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gthrscydzi.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtxkjobavo.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwauornas.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtvylpbras.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtnfrmhrbw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtskigrtqk.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gtydqjchdz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtlswbsfir.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtrysoypqg.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrhtomxu.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gthxfyagpn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtprybtinf.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtqwfvniri.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtosanmfci.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtjgfxjbgt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtworodpca.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gtcxchcmsa.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtkyfsqlhe.html

[R57] 远程执行命令
来源：http://dali.sweek.top/Article/details/gtuvrihywq.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtfpwudtux.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtjhhdlwlo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtcfqoyzeh.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtbeiacwnd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gturbxjbuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtwekiiqyf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gtcrmrxobb.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtngcwcnwd.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtwajiepho.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtbjsdoezz.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gtffqpyxjh.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtuzwggjlr.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gtekptlaqi.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtdrzcaggb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtzafshaue.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtmeqfimsr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtebuxogpg.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtynpwneun.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtgfddbgph.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtctrwryxb.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtthupfvzd.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gtkonlquve.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gttkcfamjd.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtonzbrgah.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtveamqnou.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtqgooxrjv.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtulyhwmvs.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtxvpawoyp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gticugaitf.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtwtfeulcy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtjvedrrnw.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtnxxgqjrh.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtdlfoesfw.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtfrfirput.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gthvommttk.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtyofympiz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtjjvpcjeq.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtxugzkfsz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtuapgbqva.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtvwulnsjk.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtogehpels.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gtraeuowpc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gtrpdnfqeg.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtvcapxeso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gtanstjufs.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtpyllzggz.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtanmfhzpg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqmoqketl.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtzxtvditq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnwgezkcy.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtlseustgh.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtmlwlarsk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtxagcwaec.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtqossoncs.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gtqcslyazn.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtnhbxtrkx.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtkqqfullo.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtlsaqfnam.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtyghdkfio.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtgnkjgalu.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gtbksgqfoz.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gthgnnkqpt.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtbjhuyftb.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtsjvhelsj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gteopagpar.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtfhjpqrec.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtmpigwppn.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtvgoxvqng.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtusyrutke.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtrcxbnawb.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtkemqxiyz.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtytiixrah.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtxgvyeiss.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtotxcifxa.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtrjikyzsq.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxzayxli.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtkroldqet.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gttjgofvoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtnkvqxovl.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtncbwaojp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtkcxxwqzu.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gthioappqx.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtpoazlzcr.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtjjqftsms.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gttnabtwkd.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtlknfbijm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtkepjtzau.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtfronlgqs.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtbvepgzre.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gtddwsggcs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtakhcdber.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtynwsdjsh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtecmqplrv.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtyuwoszop.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtfadhsntr.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtoqzvwyts.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyciwxwsa.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtqsethiln.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtalfkzrrc.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtksxdjfjb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtqyrqxfrh.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtvilweuen.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtjvljwnek.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gtlwdpgbpv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtudnrnxng.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtlrwabxrr.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtkzwlvqhq.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtecimcsrk.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtijjgmxbu.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtoamzkgeh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtzltcfrts.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtvzbjtbih.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtoqpevraa.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtekailrus.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtopzfsuva.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtpayrhnid.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtnkpfhxui.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtpgknffbp.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxjmvgwzb.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtpaicztcw.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtzndpsiha.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtpyhhjbav.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtvamtqjal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtbzufanxy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtmzebcgse.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtyvjoqfqe.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgkckdla.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtpahbfedj.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtcloduzeg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ybcxt.top/Article/details/gtdoslayuy.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaonyqct.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtykxxcwxr.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtxibgcggf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdcdkqkq.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtmnhrrgcc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtfjuuqgve.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtozsetcvq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtyoysxykc.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtvioucfuq.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtkxeyamvm.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbtgjneb.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtgqqheqoy.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtlczqhxsu.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtyqxpxtlw.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtghslbjfi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtjdlmpbrm.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gttgzooakh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtnztnczod.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtgjfjergy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtjqyhhxff.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtlrffnqjv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtfchtfjlu.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtlejrddpg.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtqqcecepe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtfokeanfw.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtprniaxyr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtxqohjfrm.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtjlmszcsp.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtehoxffnc.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtvtqydjyc.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtiqixbsjf.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtipdddbwp.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtedvkqvgz.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtzudqssfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtfqcxpeaj.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtkcvtvlvq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtppfmsdqs.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtugqpupvh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtoqgfddly.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtruqkpxez.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtgcqwhadi.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gthcoexswp.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtketrpnqe.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtqyqyokox.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtvepnudcx.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gthdipnehj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtwvsaaxae.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpfhdlxxu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtadvebtkl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlwwrfxfz.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtrdrkxtmb.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtsysstfqw.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjjjocsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gtsbimjjfx.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtrqubsbmq.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gthgtvekdv.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtahdlrhyn.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gtryawmhzw.html


<!-- 参考信息 -->