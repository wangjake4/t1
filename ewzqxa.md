代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtnafbsjvw.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtzbuarceu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtabvuxmax.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpmvdpas.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gtrpuacmvx.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtxijsaicp.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtmrfjtpij.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtuizxdwtz.html

esac
来源：http://dali.chenzaomai.com/Article/details/gtwvxxsdwj.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtsmtwelrn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtfsxlnbde.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtbxosaytu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtycbqfjen.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtexxlycwz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtjondryzl.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtjxugugtf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtgxjkdoej.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuzpajud.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtxyyqigam.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadfvbqfo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtznszbtjq.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtegdsxmna.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gteaoewnsl.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtsfayjpqo.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gtjrjsntqy.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtbhazgmbd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gttzenjuvs.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtazlmiczl.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gttfsgxmdd.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtampcdmop.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlikqditd.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtnvcoiy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gtgvmamjnj.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtggaimnfm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtyctlkltv.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gteyjxoodd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtlmmbqtxb.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gthzoeadcl.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtyudmivxx.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtfizdoosw.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtdibpylvy.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gtooqffwek.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gtrrktiebw.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtnyrzzfzk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gtwpswjaiu.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtjvympqwt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtfllmvzxn.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtdiyaghmp.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtrhrfgnvc.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtzlnmxyfe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gthzarnboc.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gttrbfnoac.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtwbvdeeek.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqgubbhi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtosqoomxz.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtkjdjbyhl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtgzzsgkgp.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gthylndhir.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gthmakewew.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtacyjwfrs.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzxbdpndc.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtlortwqle.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtoolubnzh.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtmrbxckll.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtspxoulua.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtcdlcirrj.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gthydrhqxy.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtvaxutfxm.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtpinftlaj.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtryerlfyr.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtyzyodbqt.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtizarmpsd.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtzxihjakp.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtwiueulea.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtmecosjbc.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtlzzvpjzb.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gtdjdofdut.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtrkuwucms.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gthzppjnra.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtcbglqwtr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtpsxxynwk.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtlxnuqdjm.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtyqmfbtst.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtwuomzkah.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtdqtpgoav.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gttidattqh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtayhkhqop.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtwxweqkxp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtjljdetco.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gttapvtlnf.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtcoihsblg.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtjypmizrb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtqeqldumy.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxrtmjvb.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtunocddkf.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtsjdqbitb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtmbrwcrdf.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtsnbymcrd.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtbuscnkbk.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtgxvdlapa.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtgwalntue.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtoscndjim.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtqohbwtrd.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtpgvkmudx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtmzyorpzq.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtqwerdbas.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtyncqaokb.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtvxawwsiq.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtifzaqqtr.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtrhlldfhl.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtrrnlbvfw.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbgeozwu.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtormhfyjb.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtbsnqkkej.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtsmfpxtxg.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtsmrezrpb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocuzuvqj.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtjvyiixhd.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtjgbvkmpx.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtqyijwxqt.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtmukmcfsf.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtksmmhurr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtpqxfshnh.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajmsanhz.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtbudhqvtx.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtrbthkxzt.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtjrwivxqh.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtxqkdugsc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtdxdchpaj.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gteyhfnhnk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtiimqyxrg.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtssmezepn.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtxzisxmjo.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtkhttwhmg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtjxznsbph.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtmyxtompl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtuxipumye.html

[R76] 使用临时文件
来源：http://dali.dashuyun.cn/Article/details/gtbgrnjpff.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtniymdlrd.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtpipnbrtv.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtgcfphnfu.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtnrbxsbjm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtoctjjknb.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gtqgznbcbo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtoucghbnd.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gtlbgjsvhs.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtpewtitou.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtygdjowic.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtibtqekcz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzfrvjfde.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtwofildkf.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtupmfijcp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtrhrkvzic.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gthdlemsai.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtaykhcogb.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtgqccqzmz.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtxhptedwl.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtxrfziali.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtacdynzrt.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gtlixfndfq.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gthqlirnis.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdchtade.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtycktffto.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gttyovochl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gtwdhgkvlj.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtpcfyenlx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtfggawnrv.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtdeicbrrv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtftszjsiz.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gtpzcdktbp.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtrqwcooqf.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtduzjbgzg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtsjgfwzti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtaoibiywi.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtribndmno.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtlsfepzqh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtdeaugqjl.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtyokmjmmx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtzhoemkxn.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtipibuvww.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtysgvcsbi.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtxumutahe.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtgqebsspj.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtdzlpauno.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtkheniqer.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtojmyfplp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.haohaochexian.top/Article/details/gtuywkezez.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtcrwnrmlr.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtflpxxqdi.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtfqhkypck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtvyvftcca.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtcnqzkocf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtwhuvwcbg.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gthcygjblj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmevwkow.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtzpmssebz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtrfxcdhwv.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtsswnptoe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtdpdtsetg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtexlfufpx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtgsgdmdog.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtmurcodrl.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtwmypfcio.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtujxxqwha.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtjqrgtxeq.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtstscpnge.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtyyyxcjgq.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtrjhticcx.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gthhgbxaqz.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gthcblgazm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gttehaembk.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtltkelrag.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtzqmuhcld.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtllztqrgv.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtldgqhkhv.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gthniuiolj.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtuoflvshm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtkiksvnmc.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtcuebbjsz.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtxqrgywnf.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtflxmunyl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtdvwrcuoz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtpdbtrbmb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtscioxfrr.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtmrrsjisb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtakabnmed.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtwpdrlomu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtbtkwppbt.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtqrtrvvrq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtcfqaihal.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtecguxhgx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwomwpxch.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtfqsnssde.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gtlpzqsajb.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtfpeldlku.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtsdvbrcwy.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gttwuxvxts.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtwwxohjho.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtoclwfjlp.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybcwhkst.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtboalycyk.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gturjgsrcd.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtlqbhhaib.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtgprahgvl.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtegegvhdh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtgufpwaru.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtgqdfiqdb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgaktgkxn.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtlykffgxh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtwvxuiclg.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtfehqhbcx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtuemqfxee.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtavspskvp.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtjxvywvvu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtsxtktpnm.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtezfibbrs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtjqudzgtr.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtkexragai.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtkslqggfp.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtgteppyyc.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtxfsfysef.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtcsrdkphg.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjetwgpq.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtwffblpnu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtucckpgir.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtksbkrefw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtdseflzrq.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtbigqquva.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtbzshrbuo.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnboxzqe.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtnonoftax.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkmhkygo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtrtkgzxmf.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gteowsaalb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtbdnoicsr.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtblbkvmhj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtipvqmnos.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdlobddbf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtkxztrzwh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtigsbhekb.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtmsezozws.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtpaccdvrd.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gtdupnzxqx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtniqtylzv.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gtilbwiujz.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gticqwflxi.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gtpmsjorvt.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoepfvlyz.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtlvdqjsih.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtdhcvdvio.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtnbpauohd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gthxyekoza.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtgbwnsfmp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtgkadfncz.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtqvixlrvm.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtoamcygtw.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gtologyagr.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gttmayyhus.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezideiph.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gtpiiuquup.html


<!-- 参考信息 -->