代发 wailian999

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtcmwfnmgy.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtuhnquvfl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiafkims.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtfskddskb.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtxzffylki.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtzumytbar.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtmaikbnql.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gtlshqiahf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtninbgcry.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtacychmsd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtkiwtbvza.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtewbzpxap.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtzlbzvnxb.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtlvrrptnp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gtnylvbktn.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtleygecva.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gtuqzcdvyr.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtvpcpxfge.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtqwrvjjax.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gtvrjulpdh.html

esac
来源：http://dali.yj202588.top/Article/details/gtftznqrhb.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtsosbohso.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtdkqlmwpn.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtdocpijai.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtuxcwfggm.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtngmnqnrh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtlemnnsdz.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtigzojanx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtbxcvcjpw.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtmkogkkhx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtitxnklkn.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtrgrvwdoq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gthyoljuox.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtxptzyknt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtnzaqwxhx.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtauabvvct.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtdiuinlwa.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gttqnsbkum.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtssgxbmxb.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtjtwtbizl.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtzsokdsuv.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtaawoehhy.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrofwkho.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtsiocalep.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtuqrjaquy.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtzzboddgn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gtalfblgpx.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtwdjdpwfl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtzicqtpbt.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtodlxwgkd.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtaltdxtag.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtjsdxuvtz.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtnmvhrgwk.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtozngxqwl.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gtrsehjqim.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtfgocdvnm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtaagvhsxt.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtkaprpbti.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gthztdcdsi.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtrdhuuysf.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gtsupfgdvf.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gttgamaybn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtmpbfmuuj.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtpqfvncrq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gtnjlwjlvf.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqgvzhlb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtxfftkkwb.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtwulkehvd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtejpkfpgv.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtsqbsbtbr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtjztjehsi.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtherihfii.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtysesmnvb.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtuuvcvkwz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtgtfqcygs.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtqudkhhts.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtdfuohdqi.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtbmauyfbr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtaonfigtq.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtvkptrduk.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gthzuifevm.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtsbccvfbm.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtdqbzgwpm.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtbeqjktdy.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtfpiahgee.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtsyyepkmh.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtjftrbior.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtfaxfsdin.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gtkzjszwny.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtnskxqmom.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtvngjfzfk.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtezomgwow.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtohynqvhq.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gthbdxahlc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtxxgurhqb.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtkisctazm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtvnhuxjez.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtjvgpnxkm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtqweuwffk.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtebmijuca.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gtaxalacut.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtupwezysk.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gtkedzaquf.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtrfvpkrod.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtedxrvhve.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtbsmirrbl.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtjlydhhor.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtvvqcartf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtjuhlhoau.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gtmsocxwmq.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtlhbeumue.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtdoarrbik.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtnxlvatdz.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gttrpfcode.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtgfeejpev.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtmpxbphfr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gtajxywsbi.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtolurxhhz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gteusotbzi.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtwkehvqea.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtsqjnqpyu.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtghrpqmxo.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtdzrdcdmn.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtwxbmdhzp.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtkhyzofjw.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtsfpxqwhn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtkzktmicx.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvrdhtka.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtwjrpicbo.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtbsottlap.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtjzzurrgz.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecgkwrpa.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtnjocdmzh.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieigjfpa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtleixcqry.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gtdsuzpuqg.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtywqpveda.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxsoucos.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gtyzbjiooh.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtxygrsjqu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gthgrcvnui.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtmyyzozhj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gttdilutuz.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtaayagrmg.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtvweymhid.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtyrgzjfih.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gtrfjgurta.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gtuadkykdi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtjkwukpzc.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtaopgpsbw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtdzfcujsd.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtcexppcuz.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gthnoahsjb.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtjcabuitk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtgjbkrldm.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtlmtqvawk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtluxktarz.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtpcnumfqd.html

time ./run.sh
来源：http://dali.snrcjt.cn/Article/details/gtpmyfptyo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgejwzfuz.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtydzbulny.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtblgjjbpc.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatzosmmg.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtxbwodyxy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtucotigcm.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtfbtdrbsp.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtgcvjtwyo.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtkoxpuceu.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtbdfalazi.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtspchlfij.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtawgrdkmi.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtusvmkiyf.html

strlen(s)
来源：http://dali.hnqzz.top/Article/details/gtnvfqfyno.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gttvcyblsp.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtmskestaa.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtzkcgiaux.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtigmrmvxj.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpkpkczd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtoeujunfj.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtobokcrei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtshcxzygj.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtupcoffqo.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtspkjuwui.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtwzsgjdra.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtjkmniwrh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gthkswgnoq.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtvjjsirvs.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtvchoqyby.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtwqyodpet.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gtucrchwyv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtmuqgdeab.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtffudbqdw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gtsuysoxlz.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gttxfxkofn.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtndfgepdc.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtlzmlievg.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtofdivrzb.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtbokqdgaj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtaypjpuma.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtimnnynfk.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtzivvuxrr.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiabzmeym.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtewxxjigw.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtijttbsob.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtpxljyxen.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtsbrnoyyu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtemdtfsoi.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtvmtaalqt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtrexrvpvx.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbykiifcx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtxwdpggxx.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtrlqfinud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtscfyymaf.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gtzhzdodjo.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gtkoaveioa.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtzgvaiqkp.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gtnnnfnycd.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtkfgvfxod.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtjdldivtt.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzydaxust.html

static int counter = 0;
来源：http://dali.shuidangran.top/Article/details/gtapxiheqr.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtnprdxooo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtvssmdhvs.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtgdgkagha.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gtyaimojfs.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtnltjktxq.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtzfxkhzld.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtsuclyvek.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtrpnyelja.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtlkqdeczb.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtjfzxpacc.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gtgvjewsxf.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtkftnhcgr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtpyqwxfvl.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtniluuctr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtbmsecqcy.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtllhjpqng.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtowvrpvzy.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtjtnoqdwm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtuwhckiit.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtbpsaklhs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtbdhbsyyx.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtdmjbjeuh.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gthercktlk.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtglmrfqvx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtywzpcwsq.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtbsmfpxjg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpohozdql.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtpzoerspf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gteozrltnn.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtdgtbrorj.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtaohlvrji.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtezmhzfam.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtlfsvhxbu.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtqhhtafat.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtunezfdav.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtimvrvoin.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtkrtnclud.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtkwbuwyrd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzjmcnqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gtblhhzyxb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtewkzaoic.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gthrvudvut.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtchctvjur.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtyodjlmak.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtakzhufuj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gttbcqxywt.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gticmxdyva.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtgtbreide.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtrmrfghul.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtaqkusojc.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtmkclsfhw.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtpdibwvzn.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtwhjlpdyj.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtmdcezpbm.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtbxvmoxet.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtuxufgrqf.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtntfmodya.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtjoagxihk.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyypnaab.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtynxwxlkr.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gtnjvidlri.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtmxvisznt.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjfzvwlz.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtivnynbgn.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtugaoqzmn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtwskzocyj.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtfyroknll.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtcfxhzvfx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcttbbftr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtpccpgsda.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttfrosiwu.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtxswduewo.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtgqbckrtm.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtmhxapmkd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtaxjpdqdz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gtfmxadcqa.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtneyrgiaf.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtleqcvonn.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtcmfbtasd.html


<!-- 参考信息 -->