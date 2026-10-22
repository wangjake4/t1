代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2zalhjvkq.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzzruvep.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2dsjpnhnj.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgoccobo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2mzfmlhhg.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqmdkmgn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gt2rqofwnep.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgbhgmlb.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2vukxvpcq.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gt2tzncswic.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2txvfchdy.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gt2rzropvov.html

esac
来源：http://dali.cdnleiting.top/Article/details/gt2chzuteqk.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gt2xgzqaoie.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gt2gxqadkky.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gt2mrhqzeul.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2bgbgborh.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqpxpngk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2ygzitqmy.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2vbdffbsg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gt2bggrgzjy.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gt2kxcqzssr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2grrcdykh.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gt2pjpjbskc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2dvsytssq.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2tcxvnnel.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gt2sqesazih.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2cwgqjltt.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clfczzib.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gt2wfepibsf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gt2llzfollt.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2ezogiwgp.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2csirozza.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2kqmmtcih.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2yyhzjxpl.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2cbolpmrz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gt2swesvxtc.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2qvaaqfqd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gt2fscvpenp.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2jjomkjzz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gt2yyrjuflt.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gt2lkxzuzyx.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2dspugpqv.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2pryhllqg.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2wafuktzf.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gt2gncfpodq.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gt2mftmbhme.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2undlhsfr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gt2ghixclhp.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2rayfbbvt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gt2apicorps.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2safnhsnh.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gt2oivqleko.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gt2ezhsostp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2vjrsghom.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gt2cmecvajt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gt2bjnyxuts.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gt2dahqizwe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gt2saqxgctn.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2eslowkfh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gt2fkpzkjdd.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2dvqaidey.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2ipetdfuh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhizcuw.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2mlpwivay.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2ijzdfosu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gt2aqjvybmm.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2vyfrzqay.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oilzpbnj.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gt2balbhobu.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gt2icptarxv.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gt2rbjhqwph.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gt2anyaqgrm.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdwffdbx.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdhjxzjp.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gt2pwakrqzt.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gt2dsxvwtqy.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2qeknpzig.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gt2mtjoaemz.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gt2kcriwadq.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2hnptepvv.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gt2ebsrwrrq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2aysnfrpq.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhsrspxq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2utmsokcq.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gt2uizrsbwu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2ycjrdocv.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gt2vnwzwggv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gt2gtduvmbz.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2xebdjrvj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2dsialjue.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gt2jvgzgjgs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbklyueg.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdipguui.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2vwopcylf.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gt2nvovwaot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2upmvrlwd.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gt2uptsjmhn.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2pkavrfkn.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gt2jkuifmzh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gt2ekfdtbha.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2qvqbfeay.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gt2wryugtye.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gt2jygsltnr.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gt2chnwigqx.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gt2yjxhkyfo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2ubhhypii.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2udodxfmy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2nehlhtbm.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2kajltqrz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2tpxkxiqy.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2idzvzpkh.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2hmbbniun.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gt2lpwbjtwa.html

du -ah . | sort -rh | head -10
来源：http://dali.havefunace.top/Article/details/gt2rzmgfvyl.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gt2fjooalgt.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gt2uqmrcdvl.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2bsueyclq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gt2cnluedkm.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gt2fdyqwocf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gt2lfaqaufb.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2zfduhnie.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2abcbjozu.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gt2vcwbjvui.html

openssl rand -hex 16
来源：http://dali.wangdashe.top/Article/details/gt2vbprazvu.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gt2ohmzzwbp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gt2svmcpbtz.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gt2ekpjxmdx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2snfhprhx.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdrewfuq.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2fvggjugm.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2yrymepit.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gt2htejtzfp.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gt2zieygldz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfdecoyv.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2crykcddv.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gt2cngsdxha.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2vobqowxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gt2qdzgnvqj.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gt2yfywksrg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2vjylzuex.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gt2ylacsmds.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2vexiojrp.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gt2ermgfpww.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gt2yijbnvjz.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gt2makxqdpv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gt2qtxqmikg.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbfvtynk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gt2btwonqej.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gt2fwvizbok.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gt2ksjgieeq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2sveftymv.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2cfewbswh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2adxffkrf.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2bqninclz.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gt2vcftoznf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gt2dpjdgtdk.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2fnugwoov.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gt2drjkpzhm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2htbkrleo.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2lbflygtj.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gt2ntwyrzdj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2wdzfzkqt.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2ajbbmuxq.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gt2itfxqobo.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2ehlctyes.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2ptvthmxs.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gt2hkvsfmzz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gt2izsyryts.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gt2ylsbsxyv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gt2sgafkthg.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnjmuqko.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gt2rvxjnbpc.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gt2opqqmelq.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gt2kevknmtv.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2agdgzrwl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2ttbixmya.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2tjhxgzsi.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2cnaegoxd.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gt2obqizams.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2yyczhqxv.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gt2pcndplcl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgezrmby.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwtyfyzu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2cayrboue.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2djbalzde.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gt2odgsldbe.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gt2gnrevnve.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gt2vmbilvzd.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2suvsfxgx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2auwmkmbf.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2qinezglp.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2qjoluxtx.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gt2lbptdquz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uamkgrai.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvsrnkri.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2cbesscja.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gt2hrrfjgyy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gt2piilgjfm.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gt2bwstiskz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfdemkwx.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gt2kgrdcwvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqhuxxbg.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2rtxsoiya.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gt2hxvchmjp.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2vtqpadeg.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gt2fdesipxd.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gt2wnicvmdx.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gt2aqwmediw.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2egfhfmhm.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2dyqfofgd.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewlyzium.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amdoqgip.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqoczjiv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oibpyhyz.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gt2ascyhdxs.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2xsyjbysq.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gt2lnweycqh.html

#endif
来源：http://dali.xuanzx.com/Article/details/gt2gbdipukw.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2iukooebl.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gt2jhknviqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zaerehyy.html

[S32] C++：字符串
来源：http://dali.daxiang520.top/Article/details/gt2pzuwftfc.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gt2zwfttfot.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2xlcxkqia.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2lqyoymkk.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gt2mrrqpoln.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gt2yrmqihrh.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2hxnzhllx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2ookcmzvu.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzwtderg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2vafjdbxk.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2dhbuetwg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gt2oauvftyw.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfuistel.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgrgkfal.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2glhdujea.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2qsgdlldw.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gt2wliemjkv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gt2webmrkcy.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2odnfhwdn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gt2quddhkfk.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gt2egeorlur.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2afiipxgh.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gt2emzcrjny.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gt2shmoquqw.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gt2gvqzuagv.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gt2kzuxxjlh.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gt2zneagewm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2fakhqopd.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gt2gnvymxfo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gt2tbphiyft.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gt2qgkvadxt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xvdokizf.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2phljcrxa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gt2ohcyowds.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2cjurzufu.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2rurhrsux.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gt2qwhmoiih.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gt2fbsauftm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skbpkaxj.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrgrkdjp.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gt2rycsoptg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gt2zutpwofk.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gt2yeyfuzfb.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gt2rvhrtquc.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2anamjmby.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gt2ungkeecw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gt2hiwmqrgv.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gt2qdwmwxoi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmmonhbz.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubdvpfov.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvcifwby.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gt2ennrnkma.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2zdqxwbdq.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gt2jcztjxrd.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gt2nvppirrl.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gt2losloluc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gt2whzlhudw.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gt2zwakfdzy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gt2zlfxtfuw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qildplsf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tranghyr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2wwtgdwpa.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2vchnexuj.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2jokdixzg.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owlkgjpi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2lboaujoy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkoyqcla.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2vnbtmahr.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2veujndee.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gt2pvxwxcdd.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gt2sgonzqzc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gt2rfnsvexm.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tleavzca.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2ydleailm.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2evhhiwce.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gt2bckjrxea.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gt2izikfekn.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gt2wyntjabr.html


<!-- 参考信息 -->