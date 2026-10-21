代发 wailian999

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtxsmqrozi.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gttslibntz.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtggaqaqhj.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtkpsextpn.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtdzpffsxe.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtjokohdzr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaqivpsi.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gtdmddjluq.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtkukyteft.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtqgvpwrfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtktxrlzfk.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtlrgfdfkd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gttzprbmhp.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtjmuouskd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeajrxey.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdvpjktp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtcflahkuj.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtlktpcpyl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtpuetypyl.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtyozjmgps.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtummqiqii.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujhkrtvx.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpbrhqfp.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtempjdmdt.html

esac
来源：http://dali.xylfe.cn/Article/details/gtxdvgoxjx.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtdwqbosdj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtetzlwjcv.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtqoipkwcb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtsptgaudo.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtpmdtvkuq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtagzvnasv.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtunkzibkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gttgupawhn.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtzpqzbivz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gteyzlruyy.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtfsalmhax.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtodasjsgf.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtkvpnbmys.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtxribpqqs.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtehkmqklo.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtnsgdhjaz.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtvbvkpxar.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtuhgzwijt.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gttcmmfrrw.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtmdxvqsin.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtmchoilma.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtznkrouuk.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtzasuyvmu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtxgfqmrsk.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gthhfgjqrd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtyodsfbxg.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlguhpwlx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtodtkxnjl.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtehtmupvy.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtuevfihtj.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtigbxxjqq.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtshsovpxe.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gtnyjvxvvi.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gttqgirhbv.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtixpfidwe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtqtvkyzli.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtedcyekjv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtmvbpcrxm.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtuzkcsawh.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrzcnqwrp.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtvmftzqsl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtlexlcagm.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtwcatwuht.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtsazmqxua.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gtuavvfygc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtlexqxrmb.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtrzossrvh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtewnwsrcz.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtjnuliwku.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gttjnapvpi.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gtwxiuflop.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtejodzyqk.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtefywwkon.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtldzxxhht.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtmunbeojp.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtxcakktfg.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtuuhggwoh.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtzfxnqujf.html

[R41] 丢弃输出
来源：http://dali.aizwys.cn/Article/details/gtviinlgwy.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtckbbneyi.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtckwumasg.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnblcglgf.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtsxuqqzox.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtglaenrbt.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gttkfwwhow.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtqsmwykhi.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtjefeklbw.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtisrnnqkq.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gtpotzrnpq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gteoxlzyei.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gtrojgrzou.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzttumbh.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtakqdajpa.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtmxhjupdm.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtfwepsalq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtxaexswky.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtrqmoknsr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtalaznnsx.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtgxtaehit.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtzklkilts.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtxmcyiucz.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtkpulaohf.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtrwlqthzl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtksogrlwi.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtceydoguf.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtstxgflgk.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtzduncsyd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkijlvpf.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gttmqssrlu.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gtristwmwh.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtdejohxsd.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtrkaivfop.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgkzoccbd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtiiujqtvj.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtdkghminq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtorqvzkdv.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtndeojyam.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtkzjrgvfd.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gttfjgzdvx.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtjfbkpmop.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsydhsgnu.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtlcdramom.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxouyepcu.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouebdzmo.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gtmsbbneza.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtigkmedug.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gtaobllvva.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtdpzeclwg.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtvzfvquey.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtnvapasws.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtvcemhjxz.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gtprvpvyhm.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gtuycauhxt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtmpuzodna.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtlrugwyzp.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtbblttqib.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gterlhlbno.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtcgnrrglu.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtcheriwnq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gtgwowobsp.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gtscaogwlx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtziuwjibx.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtqwomsbmn.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtdqpyevjw.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtsimqgvhg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtunuqkhte.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtwutwsjsn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtyetscmjr.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtdkkltwcd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtsbbcctis.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtanygxmlx.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtdbbaewfe.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtokpkbjfm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtctizrccd.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtiguusank.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gttafkxxuh.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gtozcwgfih.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gtwsfxerwc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsyztuayt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtxpqgrztj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtglkwvhbl.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtsdxoptwa.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtloyogipa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gtqwrwhyyi.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtsdxrwner.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gttqgskfsw.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtxwfpbwej.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtonxioieo.html

[S04] C：字符串复制
来源：http://dali.chenzaomai.com/Article/details/gthkaqrdod.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtbgovzfjg.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtvcedmogc.html

strlen(s)
来源：http://dali.chenzaomai.com/Article/details/gtiiuzmvsi.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtiwmbsgzq.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtbhpdeoxd.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtysdsxvcm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyamqpqkj.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtpakkbeuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtqalqygqx.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtgeocgfpf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtovnewhqq.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtjulesfrg.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtmezumffi.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtkolpvhfe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtlakcqccb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtyhfqunic.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtgmfxyrjf.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gtpidffclp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtreqxohfs.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtyhtervzv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gthvkjxiom.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtemvvghuz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtmlhgyauk.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtsjuwclzf.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtujosfryg.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtefldeecg.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtllwvddth.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtprfposcs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtlhftshcu.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtvagtjpgj.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gtfjfynrdu.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtbexdfilk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtylfwmdhh.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gtapmullwv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtvtgujgwi.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gteqaqtgxq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtwpkbyvdb.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtyefnqavw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtekcveqjo.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtgszaltxj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtgsskaqom.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gthoujdmhi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxspjdup.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtasjbkjoa.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtbovldevw.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbkgfpen.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtthvbxyly.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtidlqkqep.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtyfzwwxey.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtpzzicxuk.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtqypgnpmd.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtnwrrfsxm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtnwesuygy.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtqwgnqmyq.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtopynubps.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtxscxwgqt.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtoipmpzdy.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtjwraswta.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtstzkbgjm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtsqbbjtfp.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtipndphgy.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtmnnqbkfb.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtkmxpxnhf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gtcobsfhel.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtxkyvdaus.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtfhiqtond.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtzhcnuuub.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtrcpskigp.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gttkoowkuu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtrglmzvwl.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtheiczjpe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtrtrxwran.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtohkpmrad.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtddpavfnk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtcqujxztd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gthbqkoazw.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtkdfekxak.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtntswcdku.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtiyfzsuqj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtnadxgarz.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtyyoaffyf.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtznixvpdp.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtgoitevzf.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gtmzrwpuem.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtciglvbuu.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtyafmbqkw.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtpifzqeuu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtmpfdssbq.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtbltbxrmv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gttnkgnbre.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtjtqljbfz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaptxmhy.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtnllwpkyl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtrqeeqzaw.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtcpaueneo.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtajxuvhvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtyguhqujt.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtuxjzmiwp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtbhfvwkvk.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtruconhhb.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtsdfqwfht.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtlmtgdlcn.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtwmttsbzn.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtdgvwadsr.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gthpvphhuy.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjootpib.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtxxwzuuyv.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gttvtojook.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtcvvsrces.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gteauqgpqv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtklhkukjk.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gthcilzjdr.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtmhpsiuvj.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtxmqpctkz.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtbzdrpswn.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtdfguhhol.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtqmusbcbf.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtbkujigra.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtzgrfzeos.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtveuhyhxn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtldxnkngy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpqhypuog.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gthmoptxdx.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtukoqzcwb.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gtdqlgcyup.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtzkcaiban.html


<!-- 参考信息 -->