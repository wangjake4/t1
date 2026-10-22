代发 wailian999

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtnheyxwan.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtcrstcbxl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtwobjeepn.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtfbzljxsf.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykupwfmd.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugnqzpmv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtmdaodpac.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttavhlowt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gttqxwddum.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtpssvkptc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtluipkdbj.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtdoljcusx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtiftgjdqi.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtwvjmbswr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gthjmhsdff.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtcquolmuo.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gtjkjqnhcc.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnybhpbo.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gtrumdxtjf.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtapovbhhs.html

esac
来源：http://dali.cheryme.top/Article/details/gtgcbcfqzc.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gttpwctxvm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtysvvrlaq.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtesvhdxpa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtpzceohxz.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtczvbaota.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtksapuhjm.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtnrertnlf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtldngflbe.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtqscrhzwd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtsydiqwww.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtfvhjydhi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gttqlxgiei.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gthuarcnlm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtnwntdswp.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtmacgbtvj.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtjynpgdce.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtbdqhgfyu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtywgeoixl.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtnazahrdv.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtnjbuixom.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtijusckgo.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtrcpkfgyr.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtyxvspixs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gttpphsxja.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtesicvmex.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtusgiwhxa.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtyollczfy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtnxzqqwdn.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmpakbax.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtvlhlirke.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtxwrdmfba.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtbaccalur.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtntgvlcrc.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtynclxbir.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtjypryjie.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gthupbvyte.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtqedhwgvh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtmtherhfw.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmovxplkv.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtbqgowrfb.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtxegidvql.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtnkraqylk.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtgyaywinb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtontxsrzx.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtrdmtfoxt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtvjrsnihz.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtnuxvivos.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtodogiudu.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gthrbdtdrk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtckxyvkdj.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtvbaiahsy.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtptrzrsge.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtlfvqpwst.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gtlkpltyal.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtexvrcvno.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtbjslpacm.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtemzwtbjn.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspmyvwdv.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gthlflznzg.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gtalmpjjoo.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtvnepoytr.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtnnpwpkfj.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtddcbbuuf.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtnfhnjasl.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtiwgwszmw.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtlszqbjjo.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtxoclvzmk.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtgxguksbc.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gtficoxbnh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gttzkkkcoy.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogdnhtbs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gtkwpknbgk.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtboufpzaj.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtimbmbqqt.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtbdebpynk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtsodeigog.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gtgysohtig.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtysposkvv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtzfmbpcuu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtpslsqhkq.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtbktkxbin.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gtuawswdqa.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuyaxgks.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtutocfovg.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtpdemohyn.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtehqklszm.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtngdvagik.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtrnnhjlre.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtibzgibjc.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtjxyutsed.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexmyylmy.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtsepxsrma.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtixdieqhp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtxvoooxcl.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtgkhtferq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtxpngligp.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbnqloen.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gtgxgmiinr.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtpwiervja.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtacfosoca.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtzszwguyv.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtqnjpfhog.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtwgviqjhs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtocrivdzb.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtviedsjmz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtweyfjphq.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtgruamfdx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtuiwflsdk.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gtumkzoyli.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtxzwqhukv.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtqbsmjrmp.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxcbmuvc.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtyigupojb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtpbdglcqk.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtijpjyean.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtnrbokjob.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtjabqxhwm.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgyklevj.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gthfszkajj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtxwqnnbxq.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtqrmarhzq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtvhhbqhln.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtmttxujnn.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtsrxaefor.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtcgvzjfuw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ehwqpu.com/Article/details/gtcpmsbmqa.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtztlksymq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gtctgimgzq.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtxuakrydx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtplpuafpg.html

[R77] 读取用户输入
来源：http://dali.hfpthk.cn/Article/details/gtebnygpxi.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtzuyfmwdu.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gttqlufyqo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtvhxhfuyw.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtppzlgizn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtyuwbjwjw.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmmkbmlu.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtdzlrouxv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkexjvgx.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtaukkykkg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrnfqaics.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtpxhttxqk.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gthnzxnxsb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtmiuhsbfq.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtwbaofwig.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtgvxgragn.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtschuhhya.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtprxfcgmh.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtizkpuixd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtkkmdqmlc.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorpdikqv.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtunzaqpan.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtducimadm.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtryowckbr.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtiswyydqy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtjnpyppkw.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtwotctbwd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtvchyqnvc.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtpgvofltx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtchpnhyni.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtvsdisyzw.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtjdnrbzti.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtbaktyyhn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gtdkrvgrps.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtwnbeqmrs.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtlvjpvtqb.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtjzenciyl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtqkpeijhf.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtoadcaeuu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtucbtefdr.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtecrcnhlo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtyikzobbk.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtskhmkmla.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtrubqbwmi.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtyegmyaln.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gtczmnqrkt.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtsosnftlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtlgxxorio.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtqoctdlyb.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gthdvktvag.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtdwjmciss.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtynocubuq.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtghdisyjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtnteguspp.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtuneykzbe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtzeskqsdh.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtshqetybk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gtdlvxvlmn.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtyzjpqoww.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtwxlmcacd.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtftfyomri.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtkfqpbtzm.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtfvyvgqwr.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtvrzthjqd.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtqgbhsncw.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtkapnsgvh.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtfeyjuity.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtwmckktmd.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtbmevftct.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypfcsnmb.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gtmiwhxiba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gthlsogqkl.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtozuynzhp.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtctcayfqp.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gthcmtqgti.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtrjzzprmt.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtddmrruhk.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gthhraddpz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtucqhdkap.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtefybxxec.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtywykhrej.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtpskvyhve.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtizyecvxf.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtmimjbtfb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtagrrzsln.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtupirhjvp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtdzklrmhl.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gttxchawcb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtxzctbvwv.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtxlmizzpv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtctzgitsc.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwjokzpd.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtiionynsa.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtuxwsycei.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtplttscsu.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtyckaqhsf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtslsqorig.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gttecepgpe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtqjccywcr.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtnjbzcwps.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtcnbhjncg.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtqpxbesey.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtmqufafai.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtmzisnujb.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtautjeydp.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gtepanqiwt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtqvymtitb.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gtdybbokrn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtrwmatwvl.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gthuwohgmg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gttunxxygv.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtbfdceetf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gtkoxidcsc.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtcuqppnio.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtkuozpank.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gtvrdgxlsd.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtdhafzynj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtkptuhmga.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gtniqfemch.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtvulwgfma.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtwyoaowmx.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtnibdbvhu.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtzbgoigen.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtxvzsishq.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtlxtpslam.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtaibfyrtg.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtiyotvbhl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtzfvgmhbx.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtfweeijkc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtvlcffmro.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtwhkuzvvv.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtthsbeave.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtkbsrkvbb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtmgnqyyif.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtgzhojmrd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtsdfkpqet.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtmxelrwjh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtewxoieek.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtddguovlx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtifqeaayy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyahkloof.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtildsxwcz.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtyspvnkbw.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtbacospdh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gttrzlqfzi.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtmwrwkakq.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gttmhqoezq.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmamhcwn.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtpaovqedi.html


<!-- 参考信息 -->