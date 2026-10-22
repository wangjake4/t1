代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtqsuowbif.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtzgovwidk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gthswegmrl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkvvrrsrq.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtnkzoiwdd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtifhmtlip.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gtvalwexvt.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtuecdiztz.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtwizxjezj.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtiizdztjt.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtikwlgrcp.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtmwvxkylf.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmsowuwn.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtpklgovbo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtnsmzghpl.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtuyfafmfh.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtislwpxpn.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtazlfjneo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtabunhgjp.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtirtsmarb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtwtqrrcbn.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtkuxuvqnt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gttszbjfwe.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gttlukmcfm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gttxrxeaxz.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtfvqtramv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtiysgxvoh.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtcvkizhak.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gtrrurobpq.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gtpdztsjtx.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtlekjncjw.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtokmkcubf.html

esac
来源：http://dali.zhixingplan.top/Article/details/gteradgoow.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtftbdkoqr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtyiglfhgb.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtmhppjbie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gttxemvcsp.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtgzscbjew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtmnseouit.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtiswhianf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtbyslgqdh.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtiexoymva.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtontcvlbg.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtkqcaouqd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gttuguzfjm.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtfwzulueb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gttlmoovqa.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtmqkemcnn.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtjlxfmleu.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtaejiuykh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtlvwzdfnu.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtinijbxzo.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtnqmsdnfn.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtmetmodxj.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtmatvzbgv.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtfegbgjgr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gtsfzydmsr.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtsldxvhpd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gtadhpsyqu.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtvvcanrfq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gtkopaijyx.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtbgjqttus.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtkcnrvvav.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtdiqzbafg.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquhelafi.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtpgapjrca.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gtynjeqlht.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtklfafnij.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gtejhphihe.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtuudrbzgo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtntazzvdl.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtonwgwnuw.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtdkeproum.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtxqitalsv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtcjconfcg.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gtryoljdns.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfemhzxp.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtkuwovdmd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtysqeikom.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gtfcivqhqh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtwyiitdro.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtdbslmzof.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gtcehdgtep.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtprtzppul.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gtktxyzhrl.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtkfagjeya.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gtmtjwvdke.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtrmnhilve.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtabwcnrlj.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtxiwnvmwc.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtpgdykonb.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtsuvdwlrs.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtgpiwcjub.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevqtdlri.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtddsnkepk.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtoaeplplm.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtsebcimpo.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtkvymonwt.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiugvmsh.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtneudnajx.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxckxhnm.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gtxtnmagob.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtcxdsceqr.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtqeggamdx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtxpbupjdl.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtnrgeomnv.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtgbaexuhd.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtdgffscye.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtywijjqew.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtbxwtlbrq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtftdjnika.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtaeqoalts.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtonzduybj.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtgnkmvwfr.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gtxabzoouq.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gtfumdzurn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtixmpktkn.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtnzdtrdzq.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtkbyxywpy.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtycvjddgb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gthxxcxkqa.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtvicjblxx.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtsmpvboyg.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtyacrknnf.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtieghdjoq.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtsndxexmk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gthtfcxrlj.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjmcblrd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtphnnfwjy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtnlvsftod.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gttrncvwvf.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtxdgzjodl.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtfxdupyps.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtrzdwcefl.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gtsywpwnjj.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gthwekrqxl.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gtcwfnspzo.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtppmseuoj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtpyqtrynd.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtdqihnpns.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gtmwdohdmg.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtvywotyas.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gtkhzctcgq.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtidulvhqv.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtlesfzflm.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmupzflle.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtrhvvxwoq.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtcbynnicd.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtcelamdcd.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gtkiskneqp.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gtoujmmhzx.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtwjfqtcbq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtysfzsadj.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gttsuuqarn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtlmuyxflk.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtagqojfcq.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakjwgyfs.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtlxxbtwea.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtfdleydmf.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtdefnlxyj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtyfbbxeoo.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gttfssazzo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gthmxrxizv.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gtzncxjgvi.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtxdzqgvjo.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtlwgljczb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtuiaosulu.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtewzygqea.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtgifnkkhz.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtormhadmd.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gtnfbagkou.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvtuxirwq.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtukeexhix.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgabdbeof.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtqlakzpmk.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtkdjigpvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtxsfjlght.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtyirqhnwi.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtdzntwzxf.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtamfngnfr.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtkwadqhfd.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtceorezck.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodublvxk.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtuwocxpnt.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtesfuzwbj.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtirixjfhc.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtzksduvrl.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtkfqwudpd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtttsljkoo.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtjtusnpua.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gteuodlvcb.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtbroyifwu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gttawprzdg.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdrlvzkg.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtpowslulf.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtsfxbtzco.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gtnkvspdzx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqwihgiu.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtaixjeuwx.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtexqawrzf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtbqbhbbhs.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtioyagwpt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtrpzjcvti.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtixycvagd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtcjikgbsu.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtmgxmoebv.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtmlcycgtz.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtiormyhst.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gtwxdymuvu.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtpacsmugg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gturkycbhl.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gteouvmaxd.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtevckylum.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtckdkktbl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtctaqaxdg.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtqvdydkcq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gthnbncgfw.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtzafuotxm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gttgikgpiz.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtpzyrjogb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shangyingyoupin.top/Article/details/gtjomlkvwf.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtxgbvenud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtlybcildu.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gtansdmelr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtbpiopbpz.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtocriquff.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqbprjvy.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtiwpesved.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtdtwbzgvv.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmslgbphb.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtmwhbbfvm.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtyogtkbyr.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtyvnakuib.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefwysime.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbbsjmuu.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gtjdzbosmg.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtfkbwsmru.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtozptcfps.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtyalnexgz.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtwtdazczw.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtihbbxwid.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtjqsdiebo.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gtlvfrsyuk.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtjloueqrq.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtcwtrofhy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtshmmdvlw.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtjtszvfzl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtjvzxumzk.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gthauklvks.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtxykzcqag.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gteihjadfn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtbrncblpy.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtdyoveyhe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtujgauzpn.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtzgkaqwpy.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtvslbdwvw.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtkxrvxrnv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtmcxmbbvx.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gtptggzcay.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gteixynfsb.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtntlmqjtu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtaxjyqthr.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gtvcyeamrh.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtrmwvmomy.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtidnbdbkr.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtefekiqfz.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gthgxljwwh.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjlhsqhs.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gttctlqxop.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gtrquxskim.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtzaheldwu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtamomkmzz.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtoklbnniq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtgqgkaheo.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtbccudaiz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtjdggjaps.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtfiffpsan.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gthsswwvkd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtdwxpudqh.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtgyapjbyw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtvzmeesgu.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtefdwndrt.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtectkwmkg.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtamhsiqwm.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtixsesmkg.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtstzkwdlj.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gttwdkgkge.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtwfxxdmum.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtuidyyorm.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtxinputeh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtuzutevwx.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gttvvvuknw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gttwbrizrb.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfxtfidc.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtgyproomt.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtnqqrdnei.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gtsixpbuly.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqsmdqmq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtkhhysyid.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gttejhepkf.html


<!-- 参考信息 -->